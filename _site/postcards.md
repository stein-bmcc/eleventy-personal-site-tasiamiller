---
title: Costa Rica Postcard Design 
layout: base
pageClass: threeCol
tags:
  - design
---
<section class="project-description">
<h1>
Costa Rica Postcard Designs
</h1>
<p>
I was tasked with designing a few postcards for Costa Rica using pictures my professor provided to the students in my graphic design course. I strived to create a balanced yet dynamic composition by cropping and arranging these images. I chose logos from the selection given to me that stood out the most against their respective background without overpowering the image.
</p>
</section>
<section class="project-img">
<h3>The following are screenshots of the final product</h3>
<figure>
  <img src="/images/Postcard01.jpg" alt="Postcard design one featuring a toucan in a tree">
    <figcaption>Postcard design one featuring a toucan in a tree</figcaption>
  </img>
</figure>
<figure>
  <img src="/images/Postcard02.jpg" alt="Image features a beautiful sunset with the costa rica logo">
    <figcaption>Image features a beautiful sunset with the costa rica logo</figcaption>
  </img>
</figure>
<figure>
  <img src="/images/Postcard03.jpg" alt="Image features a baby sloth in a tree with the costa rica logo">
    <figcaption>Image features a baby sloth in a tree with the costa rica logo</figcaption>
  </img>
</figure>
</section>
<section class="related-projects">
  <h2>More Like This</h2>
<ul>
{% for project in collections.design -%}
<li><a href="{{project.url}}">{{project.data.title}}</a></li>
{% endfor %}
</ul>
</section>
<div class="back-button">
  <h3><a href="/graphic-design">Back To Graphic Design</a></h3>
</div>