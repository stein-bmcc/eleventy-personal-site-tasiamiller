---
title: Indesign Layout Design
layout: base
pageClass: oneCol
tags:
  - design
---
<section class="project-description">
<h1>
Indesign Layout Design: Kimora Lee Simmons
</h1>
<p>
For my graphic design class, I was given the assignment of creating a two page InDesign layout focusing on any influential person of our choice and I chose Kimora Lee Simmons. For this, I used shades of pink as it is a staple color in the Baby Phat branding.
</p>
</section>
<section class="project-img">
<h3>The following is an image of the final product</h3>
<figure>
  <img src="/images/Kimora-1.jpg" alt="Layout of Kimora Lee Simmons done in Adobe InDesign">
    <figcaption></figcaption>
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