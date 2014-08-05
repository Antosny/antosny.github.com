---
layout: page
title: Ant On Y
tagline: Antosny's blog
---
{% include JB/setup %}


    
## Posts


<ul class="posts">
  {% for post in site.posts %}
    <li><span><h2>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a><h2>{{ post.description }}</li>
  {% endfor %}
</ul>




