---
layout: default
title: Annonces
---

<h1>Annonces récentes</h1>

<ul class="posts_list">
  {% for post in site.posts %}
    <li>
      <h2><a class="post_header" href="{{ post.url }}">{{ post.title }}</a></h2>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>
