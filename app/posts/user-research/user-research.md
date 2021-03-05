---
tags: false
layout: collection
title: User research
description: A history of past user research
pagination:
  data: collections.user-research
  reverse: true
  size: 50
permalink: "user-research/{% if pagination.pageNumber > 0 %}page/{{ pagination.pageNumber + 1 }}{% endif %}/"
eleventyComputed:
  eleventyNavigation:
    key: "{{ title }}"
    excerpt: "{{ description }}"
    parent: home
---