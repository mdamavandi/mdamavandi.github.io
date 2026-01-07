---
title: Case Studies
---

<ul class="project-list">
  {% for study in site.case-studies %}
    <li>
      <h3>
        <a href="{{ study.url | relative_url }}">
          {{ study.title }}
        </a>
      </h3>
      <p>{{ study.summary }}</p>
    </li>
  {% endfor %}
</ul>
