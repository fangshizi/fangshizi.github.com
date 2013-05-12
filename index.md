---
layout: page
title: 在工作中实践，在这里吐槽 
---
{% include JB/setup %}

####同事们不要轻易看，小心吐槽吐你一身:)

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>