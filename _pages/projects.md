
---
layout: default
<<<<<<< HEAD
title: <Gavin Sneyd> - Portfolio
=======
title: Gavin Sneyd - Portfolio
>>>>>>> d7431c5 (<Commit Edit>)
permalink: /projects/
---

<div class="gallery-container">
<div class="project-gallery">
    {% for project in site.projects %}
      <div class="gallery-item">
        <a href="{{ project.url | relative_url }}">
          <img src="{{ project.image | relative_url }}" alt="{{ project.title }}" />
          <p>{{ project.title}}</p>
        </a>
