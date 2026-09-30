---
layout: page
title: Current Projects
permalink: /projects/current/
---

## Active Initiatives

INADESU is actively implementing two major safe space initiatives focused on creating protective environments for vulnerable children while building community resilience.

<div class="row">
  {% for project in site.data.projects.current %}
  <div class="col-lg-6 col-12 mb-5">
    <div class="card h-100 shadow-sm border-0">
      {% if project.image %}
      <img src="{{ project.image | relative_url }}" class="card-img-top" alt="{{ project.alt }}" style="height: 300px; object-fit: cover;">
      {% endif %}
      <div class="card-body">
        <h4 class="card-title mb-2">{{ project.title }}</h4>
        {% if project.category %}
        <p class="small mb-3"><span class="badge" style="background-color: var(--primary-color);">{{ project.category }}</span></p>
        {% endif %}
        <p class="card-text">{{ project.description }}</p>
        {% if project.lead %}
        <p class="small mt-3 mb-1"><strong>Project Lead:</strong> {{ project.lead }}</p>
        {% endif %}
        {% if project.members %}
        <p class="small"><strong>Team:</strong> {{ project.members }}</p>
        {% endif %}
      </div>
    </div>
  </div>
  {% endfor %}
</div>

---

## Support Our Current Work

These initiatives depend on community participation and financial support. Whether through donations, volunteering, or partnership, you can help us scale impact.

[Donate now →](/donate/)  
[Get involved →](/about/)  
[Explore past work →](/projects/past/)
