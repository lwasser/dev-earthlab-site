---
layout: single
title: "Learn"
permalink: /learn/
header:
  overlay_color: "#333"
  cta_label: "CU Students, Enroll Now - GEOG 4100 / 5100"
  cta_url: "/meetup/"
  overlay_filter: rgba(0, 0, 0, 0.5)
  caption:
excerpt: 'Data intensive learning.'
modified: 2016-08-21T17:19:29-04:00
author_profile: false
---


## Recent code tutorials

Check out our latest code tutorials. Leave questions in the comment box at
the bottom. We'll try our best to help!

  {% for post in site.categories.tutorials limit:3 %}
  <article>
    {% if post.link %}
      <h2 class="link-post"><a href="{{ site.url }}{{ post.url }}" title="{{ post.title }}">{{ post.title }}</a> <a href="{{ post.link }}" target="_blank" title="{{ post.title }}"><i class="icon-link"></i></h2>
    {% else %}
      <h2><a href="{{ site.url }}{{ post.url }}" title="{{ post.title }}">{{ post.title }}</a></h2>
      <span class="post-date">
      {% if post.lastModified %}Last modified: {{ post.lastModified | date: "%b %-d, %Y" }}{% endif %}
      {% if post.packagesLibraries %} - Libraries: {{ post.packagesLibraries | join: ', ' %}}{% endif %}
      </span>
      <p>{% if post.description %}{{ post.description }}{% else %}{{ post.content | strip_html | strip_newlines | truncate: 120 }}{% endif %}</p>
    {% endif %}
  </article>
{% endfor %}

[View All Tutorials](/tutorials/)

## Courses
We are currently redesigning Earth Systems Analytics (GEOG 4100 / 5100). This 
course fuses key topics related to the grand challenges in science, remote sensing
and computationally intensive approaches. The course will be held in Spring 2017
at the CU Boulder campus. Stay tuned for course materials as they develop.


Questions? Tweet: @leahawasser or @mxwlj
