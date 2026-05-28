---
layout: page
title: work
subtitle: "PhD research and enterprise middleware engineering — from orchestration to the kernel."
permalink: /work/
---

<ul class="timeline">
  {% for job in site.data.experience %}
  <li class="tl-entry">
    <div class="tl-head">
      <span class="tl-role">{{ job.role }}</span>
      <span class="tl-org">{% if job.org_url != "" %}<a href="{{ job.org_url }}">{{ job.org }}</a>{% else %}{{ job.org }}{% endif %}</span>
      <span class="tl-dates">{{ job.start }}&ndash;{{ job.end }}</span>
    </div>
    {% if job.location %}<p class="tl-loc">{{ job.location }}</p>{% endif %}
    {% if job.summary %}<p class="tl-summary">{{ job.summary }}</p>{% endif %}
    <ul class="tl-points">
      {% for pt in job.points %}<li>{{ pt }}</li>{% endfor %}
    </ul>
    <ul class="tags">{% for t in job.tags %}<li>{{ t }}</li>{% endfor %}</ul>
  </li>
  {% endfor %}
</ul>

<h2 class="section-label"><span class="muted">$</span> cat education.txt</h2>
<ul class="timeline">
  {% for ed in site.data.education %}
  <li class="tl-entry">
    <div class="tl-head">
      <span class="tl-role">{{ ed.degree }}</span>
      <span class="tl-org"><a href="{{ ed.org_url }}">{{ ed.org }}</a></span>
      <span class="tl-dates">{{ ed.start }}&ndash;{{ ed.end }}</span>
    </div>
    <p class="tl-summary">{{ ed.note }}</p>
  </li>
  {% endfor %}
</ul>
