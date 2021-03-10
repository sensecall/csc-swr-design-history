---
tags: false
layout: collection
title: Workshops
description: A history of past workshops
pagination:
  data: collections.workshops
  reverse: true
  size: 50
permalink: "workshops/{% if pagination.pageNumber > 0 %}page/{{ pagination.pageNumber + 1 }}{% endif %}/"
eleventyComputed:
  eleventyNavigation:
    key: "{{ title }}"
    excerpt: "{{ description }}"
    parent: home
---