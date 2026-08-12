---
layout: default
title: "Home"
keywords:
  - psychological therapy
  - psychotherapy
  - psychologists
  - therapists
  - individuals of all ages
  - couples counseling
  - group therapy
  - safe environment
  - telehealth
  - professional therapy
  - physical symptoms
  - anxiousness
  - mood fluctuations
summary: Ocean Point Counseling provides therapy to individuals of all ages, couples and families with issues including depression, anxiety, mood disorders, ADHD, PTSD, job loss, relationships/divorce, illness, Alzheimer’s and forgiveness in Ocean City, NJ.
---

{% include hero.html %}

<hr class="my-0" style="border-top: 1px solid #2E9FD6;">

<div class="container pt-5 pb-2 text-center">
  <p class="font-mono text-muted text-uppercase small mb-3">Welcome</p>
  <p class="lead mx-auto" style="max-width:640px;">Ocean Point Counseling provides therapy to individuals of all ages, couples, and families. Please feel free to call us to find out how we can help you or your loved one.</p>
</div>

<div class="bg-light py-5">
  <div class="container">
    <p class="font-mono text-muted text-uppercase small mb-2">How we help</p>
    <h2 class="mb-5">Finding your way back to solid ground</h2>
    <div class="row align-items-center">
      <div class="col-md-6 mb-4 mb-md-0">
        <img src="{{ '/assets/imgs/ocean_city_beach.png' | relative_url }}" class="img-fluid rounded shadow-sm" alt="Ocean City, NJ sun rise over the beach">
      </div>
      <div class="col-md-6">
        <div class="mb-4">
          <h3 class="h5">The challenge</h3>
          <p class="text-muted">Life can be difficult and challenging, sometimes resulting in physical and emotional symptoms. These can include digestive symptoms, fatigue, stress, insomnia, anxiousness, and fluctuations in mood. If not addressed, they can affect relationships and work.</p>
        </div>
        <div>
          <h3 class="h5">The approach</h3>
          <p class="text-muted">Professional therapy can provide insight, solutions, and avenues to personal growth, self-empowerment, and relief. We provide a safe, non-judgmental environment where issues can be discussed, strengths recognized, and solutions implemented.</p>
        </div>
      </div>
    </div>
  </div>
</div>

<div class="py-5">
  <div class="container">
    <div class="row align-items-center">
      <div class="col-md-7 mb-4 mb-md-0">
        <p class="font-mono text-muted text-uppercase small mb-2">Our team</p>
        <h2 class="mb-3">Licensed clinicians, matched to what you need</h2>
        <p class="text-muted mb-4" style="max-width:520px;">We have worked with individuals of all ages, couples, and families with issues including depression, anxiety, mood disorders, ADHD, PTSD, job loss, relationships/divorce, illness, Alzheimer’s, and forgiveness.</p>
        <a href="{{ '/clinicians.html' | relative_url }}" class="btn btn-outline-primary">Meet the team &rarr;</a>
      </div>
      <div class="col-md-5">
        <div class="d-flex justify-content-center justify-content-md-start">
          {% for item in site.data.clinicians %}
            <img src="{{ item.image | relative_url }}" alt="{{ item.title }}" class="rounded-circle border border-white shadow-sm" style="width:64px;height:64px;object-fit:cover;margin-left:{% unless forloop.first %}-16px{% else %}0{% endunless %};">
          {% endfor %}
        </div>
      </div>
    </div>
  </div>
</div>

<div class="bg-primary text-white py-5">
  <div class="container text-center">
    <p class="font-mono text-uppercase small mb-3" style="opacity:0.8;">Ready to talk?</p>
    <h2 class="text-white mb-4">Call us today, and together, we can start the healing process.</h2>
    <a href="tel:+16092313569" class="btn btn-light btn-lg">Call {{ site.phone | strip_html }} &rarr;</a>
  </div>
</div>