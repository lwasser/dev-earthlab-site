---
layout: single
authors: [Leah A. Wasser, Naupaka Zimmerman]
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

# Learning Outcomes

* Understand the four facets of reproducibility.
  1. Organization
  2. Documentation
  3. Automation
  4. Dissemination
* Be able to apply the four facets of reproducibility to improve and create more
efficient and productive scientific workflows

****

**Estimated Time:** 1-2 hours

[Download Lesson Data](https://ndownloader.figshare.com/files/6433086
){: .btn .btn--large}
</div>

## Intro to Reproducibility: Review First

Please review the material below to prepare for class.

<a href="{{ site.basurl}}/slide-shows/1_intro-reprod-science/" class="btn btn--info" target="_blank">Introduction to Reproducible Science Slide Show </a>

> Special Thanks: This presentation was adapted from the reproducible science curriculum.
Special thanks go out to: Francois Michonneau, Hilmar Lapp, Karen Cranston, Jenny Bryan,
and others who contributed to creating this presentation.

## The Scenario

You are in a lab and a colleague has moved on to a new job and left you their
research which you are tasked by your supervisor with picking up and moving forward.
Have a look at the files that were left for you to work with and answer the following
questions:

1. Are the contents of the directory easy to understand?
2. Do you feel confident that you can easily recreate the workflow associated with the data / code?
3. Do you have access to the data? What data are available and where / how were
they collected?

Next, work with your group to document ways in which you could improve upon the
reproducibility of this project.

1. Create a list of things that would make the working directory easier to work with.
1. Break that list into general “areas” / categories of reproducibility.



<!--
{% for lesson in site.open-science %}
<h3><a href="{{ lesson.url}}">{{ lesson.title }}</a></h3>
{{ lesson.description }}

{% endfor %}
-->

<!-- Testing out listing each collection set
{% for issue in site.collections %}
  <li>
    <h6 class="post-meta">
       {{ issue[1].label }}
      {{ issue[3] }}
      {{ issue[1].date | date: "%b %-d, %Y" }}
    </h6>
    <h2>
      {{ issue[1].title }}
    </h2>
  </li>
{% endfor %}

-->
