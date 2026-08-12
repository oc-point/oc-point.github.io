---
layout: default
title: "Our Clinicians"
keywords:
  - licensed psychologists
  - depression
  - anxiety
  - abuse
  - trauma
  - life adjustments
  - life transitions
  - non-judgmental
  - holistic approach
---

## Our Clinicians

<div class="container">
  {% for item in site.data.clinicians %}
  <div class="card shadow-sm mb-4">
    <div class="card-body">
      <div class="row align-items-start">
        <div class="col-12 col-sm-3 text-center mb-3 mb-sm-0">
	  <img class="img-fluid rounded shadow-sm clinician-photo" src="{{ item.image }}" alt="{{ item.title }}" loading="lazy">
        </div>
        <div class="col-12 col-sm-9">
          <h4 class="card-title">{{ item.title }}</h4>
          <div class="mb-2">
            {% for entry in item.education %}
            <span class="badge badge-light border mr-1 mb-1 degree-badge">{{ entry.degree }}</span>
            {% endfor %}
          </div>
          <p class="card-text">{{ item.summary }}</p>
        </div>
      </div>
    </div>
  </div>
  {% endfor %}
</div>