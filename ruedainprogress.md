---
layout: page
title: Rueda in Progress
permalink: /ruedainprogress/
---

This is the page for the new Rueda blog *Rueda in progress*, which is tied closely to the performance team Los Sotoneros.

<ul>
{% for post in site.categories.progress %}
    <li><a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
</ul>
