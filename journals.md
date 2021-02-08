---
title: journals
permalink: /journals/
layout: page
excerpt: journal 
comments: false
---

{% for journal in site.journals %}
<h2>
<a href="{{ journal.url }}">
{{ journal.name }} - {{ journal.source }}
</a>
</h2>
  <p>{{ journal.content | markdownify }}</p>
{% endfor %}
