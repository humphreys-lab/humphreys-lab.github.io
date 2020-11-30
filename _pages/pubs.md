---
title: Scientific publications
blurb: We lead research into the contemporary marine carbonate system.  We also contribute to a range of related studies, including ocean acidification impacts, palaeoceanographic proxy testing, and sensor development.
layout: default
permalink: /pubs/
---

<h2>Works led by the Humphreys lab</h2>
<hr />

<div class='container'>
  {% for paper in site.data.papers_hlab %}
    <div class='col-12 mb-3'>
      <div class='card border-0 shadow'>
        <div class="card-body">
          <h5 class="card-title">
            {{ paper.title }}
          </h5>
          <p class="card-text">
            {{ paper.authors }} ({{ paper.year }})
          </p>
          <p class="card-text"><small class="text-muted">
            {{ paper.info }}
          </p>
        </div>
      </div>
    </div>
  {% endfor %}
</div>

<br />

<h2>Collaborations and previous work</h2>
<hr />

<div class='container'>
  {% for paper in site.data.papers_other %}
    <div class='col-12 mb-3'>
      <div class='card border-0 shadow'>
        <div class="card-body">
          <h5 class="card-title">
            {{ paper.title }}
          </h5>
          <p class="card-text">
            {{ paper.authors }} ({{ paper.year }})
          </p>
          <p class="card-text"><small class="text-muted">
            <i>{{ paper.journal }}</i>
            {%- if paper.volume -%}
            {{ paper.volume }}
            {%- endif -%}
            {%- if paper.pages -%}
            , {{ paper.pages }}
            {%- endif -%}
            {%- if paper.doi -%}
            , <a href="https://doi.org/{{ paper.doi }}">doi:{{ paper.doi }}</a>
            {%- endif -%}
          </small></p>
        </div>
      </div>
    </div>
  {% endfor %}
</div>
