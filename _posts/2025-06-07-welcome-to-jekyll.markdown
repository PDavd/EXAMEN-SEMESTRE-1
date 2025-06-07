---
layout: post
title:  "ATICULOS"
date:   2025-06-07 14:18:50 -0600
categories: jekyll update
---
## 💡 Articulos Destacados

{% for proyecto in site.proyectos %}
  ### {{ proyecto.title }}
  <p>{{ proyecto.description }}</p>
  <a href="{{}}">Ver más</a>
{% endfor %}


