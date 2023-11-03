---
layout: default
title: Archive
---

# Archive

Browse all posts.

{% for post in site.posts %}
  <h2>{{ post.name }}</h2>
  <ul>
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
  </ul>
{% endfor %}
