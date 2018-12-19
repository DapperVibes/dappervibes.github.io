---
layout: page
title: Rueda in Progress
permalink: /ruedainprogress/
---

This is the page for the new Rueda blog *Rueda in progress*. It comes from the inspiration of numerous teachers across the globe who are innovating in Rueda.

I have utmost respect for the [Rueda standard](http://rueda.casino/standard), but in order for something to be in a standard, it needs to be established. Much of the cutting edge of Rueda isn't standard, but still in flux and development. Much homage needs to be paid to [Boston Rueda](https://bostonrueda.com/), for pushing people to reflect on and develop Rueda structures. My hope is to build up a reference library for Rueda concepts in development and get guest instructors to help add to and share their background knowledge.

Come back soon for posts and videos on:

* Rueda Dynamica
* Infinita
* Llanta
* Moebius
* Caminando

Peace, love, Rueda,

-Craig (DapperVibes) Dolder

## Main posts

<ul>
{% for post in site.categories.progress %}
    <li><a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
</ul>

## Rueda Mixta

<ul>
{% for post in site.categories.mixta %}
    <li><a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
</ul>

## Rayas Grandes

<ul>
{% for post in site.categories.rayasgrandes %}
    <li><a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
</ul>
