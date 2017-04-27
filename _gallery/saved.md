---
layout: page
title: Visual
---
<h6>Saved</h6>
<br>
{% assign sorted_photos = site.gallery.saved | sort: "weight" | reverse %}
<ul id="gallery_row">
  {% for image in sorted_photos %}
      <a href="{{ image.url }}">
        <img class="photo" src="{{ image.image_path }}" alt="{{ image.title }}" />
      </a>
  {% endfor %}
</ul>
<br>
