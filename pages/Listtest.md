---
layout: normal
title: Test
stuff:
  - one
  - two
  - three
---
# Heading

some content

[another page](./another-page.html)
[back](./)

{% for s in page.stuff %}
 - {{s}}
{% endfor %}
