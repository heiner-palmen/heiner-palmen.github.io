---
layout: default
title: Heiner Palmen
---
# Welcome to My Blog

Software development, AI, automation, and interesting projects built over 20+ years.

## Latest Posts
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> — {{ post.date | date: "%b %d, %Y" }}
    </li>
  {% endfor %}
</ul>

[Heiner Palmen YouTube Uploader](/privacy.html) — Personal YouTube upload automation tool.

[FailFloozie Shorts Publisher](/tiktok-privacy.html) — Personal TikTok draft upload tool ([Terms](/tiktok-terms.html) · [Privacy](/tiktok-privacy.html)).

[Privacy Policy](/privacy.html)