---
layout: default
title: Proyectos
permalink: /proyectos/
---

# Proyectos

<ul>
  {% for proyecto in site.proyectos %}
    <li>
      <a href="{{ proyecto.url }}">{{ proyecto.title }}</a>: {{ proyecto.descripcion }}
    </li>
  {% endfor %}
</ul>

This is the base Jekyll theme. You can find out more info about customizing your Jekyll theme, as well as basic Jekyll usage documentation at [jekyllrb.com](http://jekyllrb.com/)

You can find the source code for the Jekyll new theme at: [github.com/jglovier/jekyll-new](https://github.com/jglovier/jekyll-new)

You can find the source code for Jekyll at [github.com/jekyll/jekyll](https://github.com/jekyll/jekyll)
