---
layout: page
title: Projects
---

{% assign project_posts = site.tags.Projects %}
{% if project_posts %}
  <ul>
    {% for post in project_posts %}
      <li><a href="{{ post.url }}">{{ post.date | date: "%B %-d, %Y" }} - {{ post.title }}</a></li>
    {% endfor %}
  </ul>
{% else %}
  <p>No project posts yet!</p>
{% endif %}
