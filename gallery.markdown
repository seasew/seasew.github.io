---
layout: default
images:
  - image_path: /images/2024_ch/03.jpg
    title: Chicago
  - image_path: /images/2024_ch/02.jpg
    title: Chicago
  - image_path: /images/2024_ch/01.jpg
    title: Chicago
---
<div class="gallery-wrapper">
  <h3 class="gallery-header">Chicago [Nov 2024]</h3>
  <ul class="gallery">
      {% for image in page.images %}
        <li>
          <img src="{{ image.image_path }}" alt="{{ image.title}}"/>
        </li>
      {% endfor %}
  </ul>
</div>