---
title: Scientific software
blurb: 
layout: default
permalink: /software/
---

## Scientific software

<hr />

<div class="container-fluid">
  {% for person in site.data.software %}
    {% include software.html %}
  {% endfor %}
</div>
