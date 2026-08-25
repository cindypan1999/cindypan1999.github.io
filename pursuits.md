---
layout: page
title: pursuits
---

{% assign pursuits_posts = site.tags.pursuits %}
{% if pursuits_posts %}
  <ul>
    {% for post in pursuits_posts %}
      <li><a href="{{ post.url }}">{{ post.date | date: "%B %-d, %Y" }} - {{ post.title }}</a></li>
    {% endfor %}
  </ul>
{% else %}
  <p>No pursuit posts yet!</p>
{% endif %}
