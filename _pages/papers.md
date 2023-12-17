---
title: Scientific publications
blurb: We lead research into the changing marine carbonate system in the present-day ocean.  We also contribute to studies on related topics including ocean acidification impacts, palaeoceanographic proxies, and sensor development.
layout: default
permalink: /papers/
---

<h2>Our key outputs</h2>
<hr />
<div class='container'>
  {% for paper in site.data.papers_hlab %}
    {% include publication.html %}
  {% endfor %}
</div>

<br />

<h2>Collaborations, earlier work and in review</h2>
<hr />
<div class='container'>
  {% for paper in site.data.papers_other %}
    {% include publication.html %}
  {% endfor %}
</div>
