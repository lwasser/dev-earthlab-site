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


  {% for category in site.data.categories[page.category]  %}
    {{ category.name }}
  {% endfor %}



  <ul>
    {% for post in site.categories.data-lessons %}
    asd
      {% if post.url %}
          <li><a href="{{ post.url }}">{{ post.title }}</a></li>
      {% endif %}
    {% endfor %}
  </ul>
