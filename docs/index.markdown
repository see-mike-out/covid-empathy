---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: default
title: 코로나19 확진자/완치자 사례 공유
permalink: /home/
---
<h3 class="center">글 목록</h3>
<ul class="collection">
  {% for post in site.posts %}
    <li class="collection-item">
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
