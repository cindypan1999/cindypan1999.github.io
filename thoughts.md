---
layout: page
title: Thoughts
---

{% assign thought_posts = site.tags.Thoughts %}
{% if thought_posts %}
  <ul>
    {% for post in thought_posts %}
      <li><a href="{{ post.url }}">{{ post.date | date: "%B %-d, %Y" }} - {{ post.title }}</a></li>
    {% endfor %}
  </ul>
{% else %}
  <p>No thought posts yet!</p>
{% endif %}
