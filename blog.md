---
layout: text_structure
title: L&S Blog
---



<div class="blogWrapper">
<!-- copied from  https://jekyllrb.com/docs/step-by-step/08-blogging/ with some modifications-->
<h1>Blog Posts</h1>
<ul>
<!-- loops though all blog posts, displays daye in a readable format and link to actual blog post  -->
  {% for post in site.posts %}
    <li>
      {{ post.date | date_to_string }}
      <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
    </li>
  {% endfor %}
</ul>
</div>



