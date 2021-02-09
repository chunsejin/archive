---
title: Lectures
permalink: /lectures/
layout: page
excerpt: lectures 
comments: false
---

* **Data structure**, Spring semester 2021 ([Lecture materials](/lectures/2021-spring-data-structure/))
* **Computer networks**, Spring semester 2021

{% for lecture in site.lectures %}
<h2>
<a href="{{ lecture.url }}">
{{ lecture.name }}
</a>
</h2>
{% endfor %}

