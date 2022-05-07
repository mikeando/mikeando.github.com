---
layout: default
title: Welcome
---

{% for section in site.sections %}
# {{ section.title }}
{{ section.content }}

{% endfor %}

# Projects
{% for project in site.projects %}
## {{project.title}}
{{ project.content }}