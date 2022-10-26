---
layout: page
title: Articles
exclude_from_search: true
paginate:
  collection: posts
image: /images/heroes/hero.jpg
image_hero: /images/heroes/hero.jpg
rainbow_hero: true
---

{% assign posts = paginator.resources %}
{% render "bulmatown/collection", collection: posts, metadata: site.metadata %}

{% render "bulmatown/pagination", paginator: paginator %}
