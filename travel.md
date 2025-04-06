---
layout: page
title: Travel
---

{% assign travel_posts = site.tags.Travel %}
{% if travel_posts %}

  <ul>
    {% for post in travel_posts %}
      <li><a href="{{ post.url }}">{{ post.date | date: "%B %Y" }} - {{ post.title }}</a></li>
    {% endfor %}
  </ul>
{% else %}
  <p>No travel posts yet!</p>
{% endif %}