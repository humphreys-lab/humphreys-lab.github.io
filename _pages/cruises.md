---
title: Science at sea
layout: default
permalink: /cruises/
---

## Research expeditions
<hr />

<div class='row'>
{% for cruise in site.data.cruises %}
  <div class='col-12 col-md-6 mb-5'>
    <div class='card border-0 shadow'>
      <div class="row no-gutters">
          <div class="col-3">
            <img src="https://raw.githubusercontent.com/humphreys-lab/humphreys-lab.github.io/main/images/cruise-globes/cruise-globe-{{ cruise.code }}.png" class="img-fluid" style="max-height: 100px;" alt="Cruise map" />
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
                —{{ cruise.date_to }}
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
