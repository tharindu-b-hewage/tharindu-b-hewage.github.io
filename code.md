---
layout: page
title: code
subtitle: "Open-source systems — orchestration, CPU power, distributed compute, simulation."
permalink: /code/
---

<ul class="project-list">
  {% for p in site.data.projects %}
  <li class="project">
    <a class="project-name" href="{{ p.url }}">{{ p.name }}</a>
    <p class="project-blurb">{{ p.blurb }}</p>
    <ul class="tags">{% for t in p.tags %}<li>{{ t }}</li>{% endfor %}</ul>
  </li>
  {% endfor %}
</ul>

<p style="margin-top:2rem;"><span class="muted">$</span> more at
<a href="{{ site.profiles.github }}">github.com/tharindu-b-hewage</a> and
<a href="https://github.com/orgs/crunchycookie/repositories">github.com/crunchycookie</a>.</p>
