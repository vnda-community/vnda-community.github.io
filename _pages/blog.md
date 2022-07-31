---
layout: archive
title: "Blog"
permalink: /blog
author_profile: true
header:
  overlay_image: ../images/banner.png
  overlay_filter: 0.1 # same as adding an opacity of 0.5 to a black background
  thumbnail: logo_vnda.png
---

<div id="home">
  <h1>Latest</h1>
  <ul class="posts">
    {% for post in site.posts %}
      <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
  <h1>Categories</h1>
</div>

<style>
td, th {
   border: none!important;
}
th {
    background: #f6f0f0;
    word-wrap: break-word;
    text-align: center;
    font-size: 1px;
}
tr:nth-child(1) { 
  background:  #f6f0f0; 
  font-size: 40px;
  text-align: center;
}
tr:nth-child(2) {
  background: #f6f0f0;
  font-size: 20px;
  text-align: center;
}
</style>


| <!-- -->                                                                                                       | <!-- -->       <!-- -->                                                                                                           | <!-- -->                                                                                |
|----------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------|
| <a href="/tags#thị-giác-máy-tính-computer-vision "><img src="/images/blog/cv_thumbnail.png" width="200" /></a> | <a href="/tags#xử-lý-ngôn-ngữ-tự-nhiên-natural-language-processing "><img src="/images/blog/nlp_thumbnail.png" width="200" /></a> | <a href="/tags#điểm-báo "><img src="/images/blog/news_thumbnail.png" width="200" /></a> |
| Thị giác máy tính                                                                                              | Xử lý ngôn ngữ tự nhiên                                                                                                           | Điểm báo                                                                                |

