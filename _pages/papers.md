---
title: Scientific publications
blurb: We lead research into the changing marine carbonate system in the present-day ocean.  We also contribute to a range of related studies, including ocean acidification impacts, palaeoceanographic proxies, and novel sensor development.
layout: default
permalink: /papers/
---

<h2>Studies led by the Humphreys lab</h2>
<hr />
<div class='container'>
  {% for paper in site.data.papers_hlab %}
    {% include publication.html %}
  {% endfor %}
</div>

<br />

<h2>Collaborations and earlier work</h2>
<hr />
<div class='container'>
  {% for paper in site.data.papers_other %}
    {% include publication.html %}
  {% endfor %}
</div>
