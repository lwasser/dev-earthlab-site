---
layout: post-by-category
category: [data-lessons]
title: "Data Lessons"
permalink: /data-lessons/
comments: false
author_profile: false
---

## Open Science Class Activity test

  {{ page.teaser }}
 {{ page.category }}


  {% for category in site.data.categories %}

  - {{ category.slug }}{{ category.name }}

  {% endfor %}



  {% for category in site.data.categories %}
  <li><a name="{{ category | first }}">{{ category | first }}</a>
    <ul>
    {% for posts in category %}
      {% for post in posts %}
        <li><a href="{{ post.url }}">{{ post.title }}</a></li>
      {% endfor %}
    {% endfor %}
    </ul>
  </li>
{% endfor %}
