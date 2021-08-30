---
layout: default
tags: [Machine Learning, Utility AI, coding, Battle Royale, Python, NLP]
---


<!-- This loops through the paginated posts -->
{% for post in paginator.posts %}
  <h3><span class="date">{{ post.date | date_to_string | append: '          ' | truncate: 22}}</span><a href="{{ post.url }}">{{ post.title }}</a></h3>

{% endfor %}