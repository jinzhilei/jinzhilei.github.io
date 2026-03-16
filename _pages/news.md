---
layout: page
title: News
permalink: /news/
description: Lab news, academic events, and updates from the field of computational systems biology.
nav: true
nav_order: 5
---

{% assign news_posts = site.posts %}
{% if news_posts.size == 0 %}
  <p>No news yet. Check back soon!</p>
{% else %}
  {% for post in news_posts %}
    <div class="news-item mt-3 mb-4">
      <h5><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h5>
      <p class="text-muted small">{{ post.date | date: "%B %d, %Y" }}{% if post.categories %} · {% for cat in post.categories %}{{ cat }}{% unless forloop.last %}, {% endunless %}{% endfor %}{% endif %}</p>
      <p>{{ post.excerpt | strip_html | truncate: 200 }}</p>
    </div>
  {% endfor %}
{% endif %}
