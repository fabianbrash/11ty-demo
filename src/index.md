---
title: "Hello World"
layout: "base.njk"
---

Hello and welcome to 11ty.

{% for post in collections.posts %}

- [{{ post.data.title }}]({{ post.url }})
  {% endfor %}