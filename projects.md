---
layout: default
title: Projects
permalink: /projects/
---
# Projects

<ul>
{% for page in site.pages %}
  {% if page.url != '/projects/' and page.url contains '/projects/' %}
    <li><a href="{{ page.url }}">{{ page.title }}</a></li>
  {% endif %}
{% endfor %}
</ul>

*I'm working on it!* =^._.^=