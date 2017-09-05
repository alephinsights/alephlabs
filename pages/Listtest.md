---
layout: normal
title: List Test
stuff:
  - one
  - two
  - three
list: [1 2 3 4 5 6]
---
# list of pages
{% for s in site.pages %}
 - {{s}}
{% endfor %}
# list of things
{% for s in page.stuff %}
 - {{s}}
{% endfor %}
# list of categories
{% for s in page.categories %}
 - {{s}}
{% endfor %}
