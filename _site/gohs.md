---
title: God Of HighSchool Show Website Prototype
layout: base
tags:
  - ux
  
---
<section class="project-description">
<h1>
TV SHOW WEBSITE PROTOTYPE
</h1>
<p>
For this project, I was tasked with creating a two-page layout for a show of my choice. This assignment was a way to test how well we could follow a layout blueprint. I used one of my favorite anime, “God of High School” because I wanted to challenge myself with a longer layout. I also chose "God of High School" because it deserves more credit and attention than it received at the time of release. I made a prototype using Figma before translating it to HTML and CSS. 
</p>
</section>
<section class="project-img">
<h3>The following are screenshots of the final product</h3>
<img src="/images/gohs about.jpg" alt="The About Page">
<img src="/images/gohs episodes.jpg" alt="episodes">
</section>

<section class="related-projects">
  <h2>More Like This</h2>
<ul>
{% for project in collections.ux -%}
<li><a href="{{project.url}}">{{project.data.title}}</a></li>
{% endfor %}
</ul>
</section>
