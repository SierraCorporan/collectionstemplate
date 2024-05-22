---
title: Home
layout: base.njk
tags: navItem
---

This is the home page. Replace this with your text.

<ul>
{% for post in collections.post %}
<li>
   <a href="{{ post.url }}">{{ post.data.title }} by {{ post.data.author }}</a>
</li>
{% endfor %}
</ul>
