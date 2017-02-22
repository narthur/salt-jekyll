---
layout: page
title: Style Guide
permalink: /style-guide/
amp-plugins: [ accordion ]
---

{% assign atoms     = site.style_guide | where_exp:"component", "component.layer == 'atom'" %}
{% assign molecules = site.style_guide | where_exp:"component", "component.layer == 'molecule'" %}
{% assign organisms = site.style_guide | where_exp:"component", "component.layer == 'organism'" %}

## Atoms

{% for component in atoms %}
  <h3>{{ component.name }}</h3>
  {{ component.content }}
{% endfor %}

## Molecules

{% for component in molecules %}
  <h3>{{ component.name }}</h3>
  {{ component.content }}
{% endfor %}

## Organisms

{% for component in organisms %}
  <h3>{{ component.name }}</h3>
  {{ component.content }}
{% endfor %}

## Templates

## Pages
