---
layout: archive
title: "Blog"
permalink: /blog/
author_profile: true
header:
  overlay_image: ../images/banner.png
  overlay_filter: 0.1 # same as adding an opacity of 0.5 to a black background
---

<div id="home">
  <h1>Blog Posts</h1>
  <ul class="posts">
    {% for post in site.posts %}
      <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
</div>