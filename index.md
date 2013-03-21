---
layout: page
title: TJ Griffin
tagline: Procrastinating Since 1970
---
{% include JB/setup %}

    
## What's Up

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>




