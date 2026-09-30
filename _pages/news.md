---
layout: page
title: News
permalink: /news/
---

Stay updated on INADESU's latest work, impact stories, and insights from the field. Our news section covers project updates, policy advocacy, team spotlights, and research from our departments.

---

<div class="row">
  {% for post in site.posts %}
  <div class="col-lg-4 col-12 mb-4">
    {% include news-card.html post=post %}
  </div>
  {% endfor %}
</div>

{% if site.posts.size == 0 %}
<div class="alert alert-info" role="alert">
  No articles yet. Check back soon for updates from INADESU!
</div>
{% endif %}


