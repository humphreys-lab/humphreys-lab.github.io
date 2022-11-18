---
title: Research team
blurb: 
layout: default
permalink: /people/
---

## Current group members

<hr />

<div class="container-fluid">
  {% for person in site.data.people %}
    {% include person.html %}
  {% endfor %}
</div>

<br />

## Open positions

<hr />

### PhD positions and postdocs

We will soon be recruiting for a 3-year postdoc both as part of the [NoSE project](https://www.nioz.nl/en/news/how-coastal-seas-help-the-ocean-in-absorbing-carbon-dioxide-from-the-atmosphere)!  More information will follow soon but please feel free to get in touch already if you might be interested.

### Masters projects

If you are looking for a Masters-level research project in the Netherlands related to our work, please get in touch!

<br />

## Alumni

<hr />

#### NIOZ Texel

Masters research students from various Dutch universities supervised at the NIOZ since 2021.

<div class="row">
  {% for alumnus in site.data.alumni_nioz %}
    {% include alumnus.html %}
  {% endfor %}
</div>

#### University of Southampton

Masters research students supervised by Matthew Humphreys from 2011 to 2017 at the University of Southampton.

<div class="row">
  {% for alumnus in site.data.alumni_soton %}
    {% include alumnus.html %}
  {% endfor %}
</div>
