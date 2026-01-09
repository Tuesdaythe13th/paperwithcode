---
layout: page
permalink: /repositories/
title: repositories
description: A curation of open-source research, tools, and forensic evaluation suites.
nav: true
nav_order: 4
---

{% if site.data.repositories.github_users %}

## GitHub users

<div class="repositories row row-cols-1 row-cols-md-2 g-4">
  {% for user in site.data.repositories.github_users %}
    <div class="col mb-4">
      {% include repository/repo_user.liquid username=user %}
    </div>
  {% endfor %}
</div>

---

{% if site.repo_trophies.enabled %}
{% for user in site.data.repositories.github_users %}
{% if site.data.repositories.github_users.size > 1 %}

  <h4>{{ user }}</h4>
  {% endif %}
  <div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% include repository/repo_trophies.liquid username=user %}
  </div>

---

{% endfor %}
{% endif %}
{% endif %}

{% if site.data.repositories.github_repos %}

## GitHub Repositories

<div class="repositories row row-cols-1 row-cols-md-2 row-cols-lg-3 g-4">
  {% for repo in site.data.repositories.github_repos %}
    <div class="col mb-4">
      {% include repository/repo.liquid repository=repo %}
    </div>
  {% endfor %}
</div>
{% endif %}
