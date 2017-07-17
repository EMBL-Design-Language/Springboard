---
layout: default
title: The full menu
subtitle: "Everything in the EMBL Design Language Springboard"
group: "not_in_local_navigation"
order: 0
---
{% comment %}
We construct the site naviagion by loading a list of the site's pages
and filtering to just those with the front matter of:
  group: "in_local_navigation"
and we order by adding
  order: 2 (whatever number)
{% endcomment %}
{% assign navigation_list = site.pages | sort:"order" %}
{% assign group = 'in_local_navigation' %}
{% for node in navigation_list %}
  {% if group == null or group == node.group %}
  <h5><strong><a href="{{ site.baseurl }}{{node.url}}">{{node.title}}</a></strong></h5>
  <p>{{node.subtitle}}</p>
  {% endif %}
{% endfor %}
{% assign pages_list = nil %}
{% assign group = nil %}
