---
layout: page
title: Jornadas
---

# Jornadas de AlhambraMakers!

Jornadas realizadas - [subscríbete a nuestro rss]({{ site.url }}/jornadas.xml)

<ul>
 {% for post in site.posts %}
    {% if post.tags contains "jornadas" %}
   <li><a href="{{ site.url }}{{ post.url }}">{{post.date | date: site.customdate }} | {{ post.title }}</a></li>
    {% endif %}
 {% endfor %}
</ul>
