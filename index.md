---
layout: default
title: Inicio
permalink: /
---

# Bienvenido a Bella Boutique

Este es el sitio web oficial de nuestra empresa.  
Conoce más sobre nosotros, nuestros productos y cómo contactarnos.

---

## Nuestros Proyectos

<ul>
  {% for proyecto in site.proyectos %}
    <li>
      <h3>{{ proyecto.title }}</h3>
      <p>{{ proyecto.descripcion }}</p>
      <p>{{ proyecto.content }}</p>
    </li>
  {% endfor %}
</ul>

---


## Navegación

- [Misión y Visión]({{ '/about/' | relative_url }})
- [Catálogo de Productos]({{ '/catalog/' | relative_url }})
- [Contacto]({{ '/contact/' | relative_url }})



