---
layout: default
title: "&hellip;"
---
# &#x2626; Your Heresy Is &hellip;
A catalog of documented heresies over the ages.
{% for heresy in site.h %}
- [{{ heresy.name }}]({{ heresy.url }})
{% endfor %}