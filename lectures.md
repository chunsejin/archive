---
title: Lectures
permalink: /lectures/
layout: page
excerpt: lectures 
comments: false
---

* **Data structure**, Spring semester 2021 ([Lecture materials](/lectures/2021-spring-data-structure/))
* **Computer networks**, Spring semester 2021

{% for journal in site.journals %}
<h2>
<a href="{{ journal.url }}">
{{ journal.name }} - {{ journal.source }}
</a>
</h2>
  <p>{{ journal.content | markdownify }}</p>
{% endfor %}

