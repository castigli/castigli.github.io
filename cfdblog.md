---
layout: page
title: CFD Blog
---

As of now mostly a collection of fun pictures and movies.

<div class="posts">
  {% for post in site.posts %}
  <div class="post">
    <!-- <li> -->
      <a href="{{ post.url }}">
        {{ post.title }}
      </a><span class="post-date">{{ post.date | date_to_string }}</span>
    <!-- </li> -->
    <p>{{ post.excerpt }}</p>   
  </div>  
  {% endfor %}
</div>
