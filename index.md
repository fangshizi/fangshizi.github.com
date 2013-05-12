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
<iframe width="100%" height="50" class="share_self"  frameborder="0" scrolling="no" src="http://widget.weibo.com/weiboshow/index.php?language=&width=0&height=550&fansRow=2&ptype=1&speed=0&skin=1&isTitle=0&noborder=1&isWeibo=0&isFans=0&uid=1657256515&verifier=2275239b&dpc=1"></iframe>
