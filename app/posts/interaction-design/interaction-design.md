---
tags: false
layout: collection
title: Interaction design
description: Prototypes for the Social worker recording project
pagination:
  data: collections.interaction-design
  reverse: true
  size: 50
permalink: "interaction-design/{% if pagination.pageNumber > 0 %}page/{{ pagination.pageNumber + 1 }}{% endif %}/"
eleventyComputed:
  eleventyNavigation:
    key: "{{ title }}"
    excerpt: "{{ description }}"
    parent: home
---