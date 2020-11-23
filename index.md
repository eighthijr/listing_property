---
layout: default
title: "Happy Jekylling!"
---

## You're ready to go!

Start developing your Jekyll website.

<ul>
  {% for post in site.listings %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

<ul>
  {% for post in site.blog %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>