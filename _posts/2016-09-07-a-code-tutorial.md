---
layout: single
author: [Leah A. Wasser, Maxwell Joseph]
category: [tutorials]
title: 'Code Tutorial'
excerpt: 'About this tutorial...'
sidebar:
  nav:
author_profile: false
comments: false
---

{% for author in site.data.authors %}
{{ author.name }}{{ author.slug }}
{% endfor %}


New stuff

{% assign author =  site.data.authors.[page.author] %}
{{ author }}


The Authors
{% for anAuthor in page.author %}
{{ anAuthor }}
{% assign author =  site.data.authors.[anAuthor] %}
{{ author }}
{{ author.slug }}
{% endfor %}



Code tutorial stuff here

```r
# Code
more <– 1+2
```
