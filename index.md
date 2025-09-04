---
layout: default
title: Inicio - Risk Investigator
---

# ¡Bienvenido a Risk Investigator!

Explora mi blog para encontrar artículos y reflexiones sobre finanzas, contabilidad, riesgo financiero, bienes raíces y mucho más.

---

### Última Entrada del Blog

{% for post in site.posts limit:1 %}
  <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
  <p class="post-date">{{ post.date | date: "%-d de %B de %Y" }}</p>
  <p>{{ post.excerpt }}</p>
{% endfor %}