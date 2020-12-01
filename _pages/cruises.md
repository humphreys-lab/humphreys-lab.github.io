---
title: Science at sea
blurb: Collecting and measuring seawater samples to better understand the changing marine carbon cycle is at the heart of our mission.  We travel around the world on research ships to this end.
layout: default
permalink: /cruises/
---

## Research expeditions
<hr />

<div class='row'>
{% for cruise in site.data.cruises %}
  <div class='col-12 col-md-6 mb-4'>
    <div class='card border-0 shadow'>
      <div class="row no-gutters">
          <div class="col-12 col-md-5 text-center">
            <img src="https://raw.githubusercontent.com/humphreys-lab/humphreys-lab.github.io/main/images/cruise-globes/cruise-globe-{{ cruise.code }}.png" class="img-fluid" style="max-height: 350px;" alt="Cruise map" />
          </div>
          <div class="col">
          <div class="card-body">
              <h5 class="card-title">{{ cruise.code }} ({{ cruise.vessel }})</h5>
              <p class="card-text">
              {{cruise.blurb}}
              <br />
              <small>
                {{ cruise.date_from }}
                {%- if cruise.date_to -%}
                –{{ cruise.date_to }}
                {%- endif -%}
              </small>
              </p>
          </div>
          </div>
      </div>
    </div>
  </div>
{% endfor %}
</div>
