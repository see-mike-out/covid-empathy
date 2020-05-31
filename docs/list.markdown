---
layout: default
title: 사례들
---
# 사례들
<section id="articles">
  {% for post in site.posts %}
    <article style="padding: 10px; border-radius: 5px; border: 1px solid #dddddd; margin-bottom: 7px;">
      <a href="{{ post.url }}" style="font-size: 1.5rem; font-weight: bold">{{ post.title }}</a><br/>
      <span style="color: #ffffff; background-color: #1976d2; font-size: 0.9rem; padding: 2px 1px 2px 4px; border-radius: 3px; margin-right: 5px;"> {{post.categories}} </span> <span style="color: #454545; font-size: 0.9rem;">{{ post.date | date: '%Y년 %-m월 %-d일' }}</span>
    </article>
  {% endfor %}
</section>
