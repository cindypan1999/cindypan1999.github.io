---
layout: page
title: Highlights
---

{% assign highlight_posts = site.tags.Highlights %}
{% if highlight_posts %}
  <ul>
    {% for post in highlight_posts %}
      <li><a href="{{ post.url }}">{{ post.date | date: "%B %-d, %Y" }} - {{ post.title }}</a></li>
    {% endfor %}
  </ul>
{% else %}
  <p>No highlights yet!</p>
{% endif %}
