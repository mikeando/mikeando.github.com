---
layout: default
title: Welcome
---

{% for section in site.sections %}
# {{ section.title }}
{{ section.content }}

{% endfor %}

# Work Projects
{% for project in site.work %}
{% if project.icon != nil %}
## <img src="{{project.icon}}" class="icon"> {{project.title}}
{% else %}
## <img src="{{project.icon}}" class="icon"> {{project.title}}
{% endif %}
{{ project.content }}
# Personal Projects

{% for project in site.projects %}
{% if project.icon != nil %}
## <img src="{{project.icon}}" class="icon"> {{project.title}}
{% else %}
## <img src="{{project.icon}}" class="icon"> {{project.title}}
{% endif %}
{{ project.content }}

{% endfor %}