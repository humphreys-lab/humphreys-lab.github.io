---
title: Research team
blurb: 
layout: default
permalink: /people/
---

## Current lab members and associates

<hr />

<div class="container-fluid">
  {% for person in site.data.people %}
    {% include person.html %}
  {% endfor %}
</div>

<br />

## Open positions

<hr />

If you are looking for a Masters-level guided research project in the Netherlands related to our work, please get in touch!

<br />

## Alumni

<hr />

#### University of Southampton

Masters research students supervised at the University of Southampton from 2011 to 2017, plus their (approximate) thesis titles.

<div class="row">
  {% for alumnus in site.data.alumni %}
    {% include alumnus.html %}
  {% endfor %}
</div>
