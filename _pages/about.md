---
layout: page
title: About
permalink: /about/
---

## Who We Are

{{ site.data.organisation.name }} ({{ site.data.organisation.abbreviation }}) is a grassroots organization working across Cameroon to advance human rights, education, health, economic opportunity, and sustainable development for marginalized communities.

**Leku Sylvie Nakou** founded INADESU with a commitment to inclusive development and human rights. Her leadership shapes the organization's work across health, education, economic empowerment, and advocacy initiatives. Sylvie's vision is grounded in direct community engagement and respect for local knowledge and agency.

Based in Buea, South West Region, we work directly with individuals and communities to identify their needs and co-create solutions that build dignity, resilience, and self-determination.

---

### Our Mission

{{ site.data.organisation.mission }}

---

### Our Vision

{{ site.data.organisation.vision }}

---

### How We Work

We organize our work through five interconnected departments, each addressing critical aspects of community wellbeing:

<div class="row">
  {% for dept in site.data.departments %}
  <div class="col-lg-6 col-12 mb-4">
    <div class="card h-100 p-4">
      <h5 class="card-title">{{ dept.name }}</h5>
      <p class="card-text">{{ dept.description }}</p>
    </div>
  </div>
  {% endfor %}
</div>

**We believe these areas are deeply interconnected.** Health depends on education and economic security. Advocacy without direct service misses communities in crisis. Education without economic opportunity leaves young people stranded. Our integrated approach recognizes that sustainable change requires working across all five pillars.

---

### How You Can Support

#### Volunteer

We welcome volunteers with diverse skills. Current opportunities include:

- **Education** – Tutoring, curriculum development, school program support
- **Health** – Health awareness facilitation, peer education, health worker support
- **Communication** – Writing, social media, documentation, translation
- **Administration** – Project coordination, data management, event planning
- **Technology** – Website support, digital training, tech troubleshooting

[Learn more about volunteering](/contact/)

#### Make a Donation

Your financial support enables our work in communities. Every donation—whether one-time or monthly—directly funds programs in health, education, economic empowerment, and advocacy.

[Support INADESU](/donate/)

#### Partner With Us

We collaborate with government agencies, academic institutions, corporate partners, international NGOs, and community organizations. Partnership models include:

- Co-implementation of programs
- Capacity building and training
- Research and documentation
- Policy advocacy and systems change
- In-kind contributions and workplace giving

[Get in touch about partnerships](/contact/)

#### Advocate for Change

Policy change is essential for sustainable impact. You can support INADESU's advocacy work by:

- Following and sharing our policy analysis
- Contacting elected representatives on issues we highlight
- Amplifying community voices on social media
- Contributing to policy discussions and research

---

### Contact Us

**Location:**  
{{ site.data.organisation.address }}

**Phone:**  
[{{ site.data.organisation.telephone }}](tel:{{ site.data.organisation.telephone | replace: ' ', '' }})

**Email:**  
[{{ site.data.organisation.email }}](mailto:{{ site.data.organisation.email }})

---

Want to learn more? [Explore our current projects](/projects/) or [read our latest stories](/news/).
