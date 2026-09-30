---
layout: page
title: Past Projects
permalink: /projects/past/
---

## Our Journey & Impact

From 2016 to the present, INADESU has implemented nine completed projects across health, education, economic development, and gender equality. These initiatives have built the foundation for our current work and continue to shape our approach to community development.

<div class="row">
  {% for project in site.data.projects.past %}
  <div class="col-lg-4 col-md-6 col-12 mb-5">
    <div class="card h-100 shadow-sm border-0">
      {% if project.image %}
      <img src="{{ project.image | relative_url }}" class="card-img-top" alt="{{ project.alt }}" style="height: 250px; object-fit: cover;">
      {% endif %}
      <div class="card-body d-flex flex-column">
        <h5 class="card-title">{{ project.title }}</h5>
        {% if project.year %}
        <p class="small text-muted mb-2"><strong>{{ project.year }}</strong></p>
        {% endif %}
        {% if project.category %}
        <p class="small mb-3"><span class="badge" style="background-color: var(--primary-color);">{{ project.category }}</span></p>
        {% endif %}
        <p class="card-text flex-grow-1">{{ project.description }}</p>
      </div>
    </div>
  </div>
  {% endfor %}
</div>

---

## What We Learned

Each completed project contributes invaluable lessons to our ongoing work. We've learned that:

- **Community engagement matters**: The most sustainable initiatives emerge from listening to communities and working *with* them, not *for* them
- **Integrated approaches work**: Projects addressing multiple interconnected challenges (health, education, economic opportunity) create more durable change
- **Long-term commitment is essential**: Quick interventions rarely create lasting impact; sustained engagement builds trust and capacity
- **Young people are changemakers**: When equipped with skills, platforms, and belief in their power, young people drive transformation in their own communities

---

## Building on Our Foundation

All of INADESU's past projects inform our current work. The relationships built, the lessons learned, and the communities we've engaged continue to guide our strategy and commitment.

[See our current projects →](/projects/current/)  
[Join our team →](/about/)  
[Support our work →](/donate/)
