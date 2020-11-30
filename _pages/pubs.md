---
title: Scientific publications
blurb: We lead research into the contemporary marine carbonate system.  We also contribute to a wider range of studies related to this field, including ocean acidification impacts, palaeoceanographic proxy testing, and sensor development.
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
            {%- if paper.info -%}
            , {{ paper.info }}
            {%- endif -%}
            {%- if paper.doi -%}
            , <a href="https://doi.org/{{ paper.doi }}">doi:{{ paper.doi }}</a>
            {%- endif -%}
          </p>
        </div>
      </div>
    </div>
  {% endfor %}
</div>

<div class='container'>
    <div class='col-12 mb-3'>
      <div class='card border-0 shadow'>
        <div class="card-body">
          <h5 class="card-title">
            Short-term responses to ocean acidification: effects on relative abundance of eukaryotic plankton from the tropical Timor Sea
          </h5>
          <p class="card-text">
            Rahlff, J., Khodami, S., Voskuhl, L., <u>Humphreys, M. P.</u>, Stolle, C., Martinez Arbizu, P., Wurl, O. and Ribas-Ribas, M. (2020)
          </p>
          <p class="card-text"><small class="text-muted">
            <i>bioRxiv,</i> 2020.04.30.068601, <a href='https://doi.org/10.1101/2020.04.30.068601'>doi:10.1101/2020.04.30.068601</a></small>
          </p>
        </div>
      </div>
    </div>
    <div class='col-12 mb-3'>
      <div class='card border-0 shadow'>
        <div class="card-body">
          <h5 class="card-title">
            The pH dependency of the boron isotopic composition of diatom opal (<i>Thalassiosira weissflogii</i>)
          </h5>
          <p class="card-text">
            Donald, H. K., Foster, G. L., Fröhberg, N., Swann, G. E. A., Poulton, A., Moore, C. M. and <u>Humphreys, M. P.</u> (2020)
          </p>
          <p class="card-text"><small class="text-muted">
            <i>Biogeosciences</i> 17, 2825-2837, <a href='https://doi.org/10.5194/bg-17-2825-2020'>doi:10.5194/bg-17-2825-2020</a></small>
          </p>
        </div>
      </div>
    </div>
  </div>
</div>
