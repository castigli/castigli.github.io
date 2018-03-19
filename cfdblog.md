---
layout: page
title: CFD Blog
---

This blog is a collection of clips or figures which have been obtained from exploratory work, test cases, or published results.


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
