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

## Our Very Experienced Clinicians

{% for item in site.data.clinicians %}
<div class="container-fluid">
  <h4 class="text-muted">{{item.title}}</h4>
  <div class="row">
    <div class="col-sm-2">
      <img class="img-fluid" src="{{item.image}}" alt="{{item.title}}"><br>
    </div>
    <div class="col-sm-10">
      <div class="row">
	{% for entry in item.education %}
    	  <i>{{entry.degree}}</i><br>
  	{% endfor %}
        {{item.summary}} <br>
      </div>
    </div>
  </div>
</div>
<br>
{% endfor %}