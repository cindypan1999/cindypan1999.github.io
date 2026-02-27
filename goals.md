---
layout: page
title: goals
---

{% assign goal_posts = site.tags.Goals %}
{% if goal_posts %}
  <ul>
    {% for post in goal_posts %}
      <li><a href="{{ post.url }}">{{ post.date | date: "%B %-d, %Y" }} - {{ post.title }}</a></li>
    {% endfor %}
  </ul>
{% else %}
  <p>No goal posts yet!</p>
{% endif %}
