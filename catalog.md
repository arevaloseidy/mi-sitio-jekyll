---
layout: default
title: Catálogo
permalink: /catalog/
---

# Catálogo de Productos

A continuación, te presentamos algunos de nuestros productos destacados:

## Producto 1: Camiseta Azul

![Camiseta Azul]({{ '/assets/images/camiseta-azul.jpg' | relative_url }})

Descripción: Camiseta de algodón 100%, cómoda y resistente.

---

## Producto 2: Mochila Negra

![Mochila Negra]({{ '/assets/images/mochila-negra.jpg' | relative_url }})

Descripción: Mochila para uso diario, con múltiples compartimentos.

---

## Producto 3: Reloj Deportivo

![Reloj Deportivo]({{ '/assets/images/reloj-deportivo.jpg' | relative_url }})

Descripción: Reloj resistente al agua, ideal para actividades deportivas.

---

# Proyectos Destacados

Estos son algunos de nuestros proyectos recientes:

<ul>
  {% for proyecto in site.proyectos %}
  <li>
    <h2>{{ proyecto.title }}</h2>
    <p><strong>Descripción:</strong> {{ proyecto.descripcion }}</p>
    <p>{{ proyecto.content }}</p>
  </li>
  {% endfor %}
</ul>

---

[Inicio]({{ '/' | relative_url }}) |  
[Misión y Visión]({{ '/about/' | relative_url }}) |  
[Contacto]({{ '/contact/' | relative_url }})
