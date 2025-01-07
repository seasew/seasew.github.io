---
layout: default
images:
  - image_path: /images/2024/03.jpg
    title: Chicago
  - image_path: /images/2024/02.jpg
    title: Chicago
  - image_path: /images/2024/01.jpg
    title: Chicago
---
<div class="gallery-wrapper">
  <ul class="gallery">
      {% for image in page.images %}
        <li>
          <img src="{{ image.image_path }}" alt="{{ image.title}}"/>
        </li>
      {% endfor %}
  </ul>
</div>