---
layout: home
---

# Welcome to My Personal Website!

I'm Aaron Gassier, and this is my personal website.

## Latest Blog Posts

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }}) - {{ post.date | date: "%B %d, %Y" }}
{% endfor %}

## About

This website is new, its use is yet to be fully determined.