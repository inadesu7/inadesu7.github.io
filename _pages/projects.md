---
layout: page
title: Projects
permalink: /projects/
---

## Our Work in Action

INADESU implements projects across five core areas: **health, education, economic empowerment, gender equality, and advocacy**. Our work ranges from immediate community responses to long-term development initiatives, all grounded in partnership and respect for local knowledge.

Below, explore our **active initiatives** and the **foundation of completed work** that informs our approach.

---

## Current Projects

INADESU is actively implementing major safe space and community development initiatives:

<div class="row mb-5">
  {% for project in site.data.projects.current limit:2 %}
  <div class="col-lg-6 col-12 mb-4">
    <div class="card h-100 shadow-sm border-0">
      {% if project.image %}
      <img src="{{ project.image | relative_url }}" class="card-img-top" alt="{{ project.alt }}" style="height: 280px; object-fit: cover;">
      {% endif %}
      <div class="card-body">
        <h5 class="card-title">{{ project.title }}</h5>
        {% if project.category %}
        <p class="small mb-2"><span class="badge" style="background-color: var(--primary-color);">{{ project.category }}</span></p>
        {% endif %}
        <p class="card-text small">{{ project.description | truncatewords: 30 }}</p>
      </div>
    </div>
  </div>
  {% endfor %}
</div>

### [View all current projects →](/projects/current/)

---

## Past Projects

We've implemented nine completed projects since 2016, each contributing to our growing expertise and community relationships:

<div class="row mb-5">
  {% for project in site.data.projects.past limit:3 %}
  <div class="col-lg-4 col-md-6 col-12 mb-4">
    <div class="card h-100 shadow-sm border-0">
      {% if project.image %}
      <img src="{{ project.image | relative_url }}" class="card-img-top" alt="{{ project.alt }}" style="height: 220px; object-fit: cover;">
      {% endif %}
      <div class="card-body d-flex flex-column">
        <h6 class="card-title">{{ project.title }}</h6>
        {% if project.year %}
        <p class="small text-muted mb-2"><strong>{{ project.year }}</strong></p>
        {% endif %}
        {% if project.category %}
        <p class="small mb-2"><span class="badge" style="background-color: var(--primary-color);">{{ project.category }}</span></p>
        {% endif %}
      </div>
    </div>
  </div>
  {% endfor %}
</div>

### [View all past projects →](/projects/past/)

---

## Support Our Work

Each project represents months of community engagement, implementation, and evaluation. Your support enables us to scale impact and launch new initiatives.

[Donate now →](/donate/)  
[Volunteer with a project →](/about/)  
[Contact us for partnerships →](/contact/)

