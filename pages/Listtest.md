---
layout: normal
title: List Test
stuff:
  - one
  - two
  - three
---
# Heading

some content

[another page](./another-page.html)
[back](./)

{% for s in site.pages %}
 - {{s}}
{% endfor %}

{% for s in page.stuff %}
 - {{s}}
{% endfor %}
