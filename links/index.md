---
layout: page
title: Links
excerpt: "Things to check out."
---

<ul class="post-list">
{% for post in site.links %}
  <li><article><a href="{{ post.link }}">{{ post.title }}</a><p>{{ post.output }}</p></article></li>
{% endfor %}
</ul>
