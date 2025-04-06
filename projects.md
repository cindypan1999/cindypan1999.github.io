---
layout: page
title: Projects
---

{% assign project_posts = site.tags.Projects %}
{% if project_posts %}
  <h3>Travel</h3>
  <ul>
    {% for post in travel_posts %}
      <li><a href="{{ post.url }}">{{ post.date | date: "%B %Y" }} - {{ post.title }}</a></li>
    {% endfor %}
  </ul>
{% else %}
  <p>No project posts yet!</p>
{% endif %}
