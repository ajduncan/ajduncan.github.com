---
layout: page
title: ajduncan
tagline: a github presence 
---
{% include JB/setup %}

There isn't anything much to see here currently.  

## Posts.

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>


