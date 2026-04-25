---
layout: default
title: Blog
hide_title: true
---

## Neuste Posts

<ul id="blog-posts">
{% for post in site.posts %}
<li>
    <a href="{{ post.url | relative_url }}">{{ post.title }}</a><br />
    <span class="post-date">{{ post.date | date: "%d.%m.%Y" }}</span>
    <p>{{ post.excerpt }} <a href="{{ post.url | relative_url }}">weiterlesen</a></p>
</li>
{% endfor %}
</ul>
