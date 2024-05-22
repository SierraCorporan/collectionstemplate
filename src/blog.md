---
title: Blog
layout: base.njk
tags: navItem
---

### All Blog Posts

<ul>
{% for blog in collections.blog %}
<li>
   <a href="{{ blog.url }}">{{ blog.data.title }} by {{ blog.data.author }}</a>
</li>
{% endfor %}
</ul>
