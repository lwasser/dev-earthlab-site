---
layout: single
author: [Leah, Naupaka Zimmerman]
category: [data-lessons]
title: 'Open Science Data Intensive University Classroom Activity'
excerpt: 'A hands-on activity where students review a project for readability,
organization, etc and identify key elements that would make it more usable and
readily reproducible.'
sidebar:
  nav: 'open-science'
author_profile: false
comments: false
---

## Overview

<div class='notice--success' markdown="1">

## Learning Outcomes

****

**Estimated Time:**

**Other Metadata:**

[Download Lesson Data](http://#){: .btn .btn--large}
</div>


{% for lesson in site.open-science %}
<h3><a href="{{ lesson.url}}">{{ lesson.title }}</a></h3>
{{ lesson.description }}

{% endfor %}
