---
layout: page
title: Galerie
permalink: /galerie
---

<ul>
  {% for page in site.pages %} 
    {% if page.layout == 'gallery' %}
          <li><a href="{{ page.url }}">{{ page.title }}</a></li>
    {% endif %}   
  {% endfor %} 
</ul>
