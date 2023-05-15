---
title: God Of HighSchool Show Website Prototype
layout: base
pageClass: twoCol
tags:
- ux

---
<section class="project-description">
<h1>
TV SHOW WEBSITE PROTOTYPE
</h1>
<p>
For this project, I was tasked with creating a two-page layout for a show of my choice. This assignment was a way to test how well we could follow a layout blueprint. I used one of my favorite anime, “God of High School” because I wanted to challenge myself. I also chose "God of High School" because it deserves more credit and attention than it received at the time of its release. I made a prototype using Figma before translating it to HTML and CSS. 
</p>
<p>
  <a href="https://www.figma.com/proto/sBLlNArqZkziOi3QTduwMp/midterm-(Copy)?page-id=126%3A166&type=design&node-id=126-168&viewport=531%2C369%2C0.5&scaling=min-zoom"> Link To Figma View</a>
</p>
<p>
  <a href="https://mmp240.netlify.app/midtermshowsite/episodes.html">Link To Site Prototype</a>
</p>
</section>
<section class="project-img">
<h3>The following are screenshots of the final product</h3>
<figure>
<img src="/images/gohs about.jpg" alt="The About Page">
<figcaption>About Page</figcaption>
</img>
</figure>
<figure>
<img src="/images/gohs episodes.jpg" alt="episodes">
<figcaption>Episodes Page</figcaption>
</img>
</figure>

</section>
<section class="related-projects">
<h2>More Like This</h2>
<ul>
{% for project in collections.ux -%}
<li><a href="{{project.url}}">{{project.data.title}}</a></li>
{% endfor %}
</ul>
</section>
<div class="back-button">
<h3><a href="/ux-ui">Back To UX/UI Desgins</a></h3>
</div>