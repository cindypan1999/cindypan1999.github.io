---
layout: page
title: travel
---

{% assign travel_posts = site.tags.travel %}
{% if travel_posts %}

  <ul>
    {% for post in travel_posts %}
      <li><a href="{{ post.url }}">{{ post.date | date: "%B %-d, %Y" }} - {{ post.title }}</a></li>
    {% endfor %}
  </ul>
{% else %}
  <p>No travel posts yet!</p>
{% endif %}