---
layout: page
title: Articles
exclude_from_search: true
paginate:
  collection: articles
image: /images/heroes/hero.jpg
image_hero: /images/heroes/hero.jpg
rainbow_hero: true
---

{% assign articles = paginator.resources %}
{% render "bulmatown/collection", collection: articles, metadata: site.metadata %}

{% render "bulmatown/pagination", paginator: paginator %}
