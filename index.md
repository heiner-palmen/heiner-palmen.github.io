---
layout: home
title: Heiner Palmen
---

# Welcome to My Blog

Software development, AI, automation, and interesting projects built over 20+ years.

---

## Latest Posts

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> — {{ post.date | date: "%b %d, %Y" }}
    </li>
  {% endfor %}
</ul>