---
layout: default
title: Blog - Risk Investigator
---

# Entradas del Blog

{% for post in site.posts %}
  <div class="section">
    <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
    <p class="date">{{ post.date | date: "%d de %B de %Y" }}</p>
    <p>{{ post.excerpt }}</p>
  </div>
{% endfor %}
