---
layout: single
title: "Events"
author_profile: false
published: true
site-map: true
permalink: /events/
---

{% capture nowyear %}{{'now' | date: '%Y'}}{% endcapture %}
{% capture nowday %}{{'now' | date: '%j'}}{% endcapture %}


## Upcoming events

{% for event in site.events reversed %}
  {% capture eventyear %}{{event.date | date: '%Y'}}{% endcapture %}
  {% capture eventday %}{{event.date | date: '%j'}}{% endcapture %}
  {% if eventyear > nowyear or eventday >= nowday and eventyear >= nowyear %}
  <li>
    <span class="event-date">{{ event.date | date: "%b %-d, %Y" }}</span>
    <a class="event-link" href="{{ event.link }}">{{ event.title }}</a>
  </li>
  {% endif %}
{% endfor %}


## Past events

{% for event in site.events reversed %}
  {% capture eventyear %}{{event.date | date: '%Y'}}{% endcapture %}
  {% capture eventday %}{{event.date | date: '%j'}}{% endcapture %}
  {% if eventyear < nowyear or eventday < nowday and eventyear == nowyear %}
  <li>
    <span class="event-date">{{ event.date | date: "%b %-d, %Y" }}</span>
    <a class="event-link" href="{{ event.link }}">{{ event.title }}</a>
  </li>
  {% endif %}
{% endfor %}

