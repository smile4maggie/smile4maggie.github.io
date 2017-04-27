---
title: Saved
layout: gallery
galleryid: saved
image_path: /../assets/gallery/saved/
weight: 2
---
<h6>{{ page.title }}</h6>
<br>
<div id="gallery-space"></div>
{% for gallery in site.data.galleries %}
  {% if gallery.id == page.galleryid %}
    {% for image in gallery.images %}
      <img class="photo-collection" src="{{ gallery.imagefolder}}/{{ image.name }}">
    {% endfor %}
  {% endif %}
{% endfor %}
<h5>{{ content | remove: '<p>' | remove: '</p>' }}</h5>
<div id="gallery-space"></div>
<div id="gallery-space"></div>
