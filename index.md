---
layout: page
title: Inbox Airlock Blog
permalink:
---

<div>
  {% for post in site.posts %}
    <div class="py-1">
      <h3><a href="{{ post.url }}">{{ post.title}}</a></h3>
      <div class="text-sm text-gray-400">{{post.date | date: "%B %-d, %Y"}}</div>
    </div>
  {% endfor %}
</div>