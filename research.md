---
layout: page
title: research
subtitle: "Peer-reviewed systems work on sustainable cloud computing — orchestration down to hardware."
permalink: /research/
---

<p>PhD research at the <a href="http://clouds.cis.unimelb.edu.au/">CLOUDS Lab</a>,
University of Melbourne, with collaborators across TU Wien (Austria), UPM Madrid (Spain),
and UniMelb (Australia). Full list on my
<a href="{{ site.profiles.scholar }}">Google Scholar profile</a>.</p>

{% assign me = site.data.publications.me %}
{% capture bold_me %}<strong>{{ me }}</strong>{% endcapture %}
<ul class="pub-list">
  {% for pub in site.data.publications.items %}
  <li class="pub">
    <span class="pub-authors">{{ pub.authors | replace: me, bold_me }}</span>
    <span class="pub-title-main">{{ pub.title }}</span>
    <span class="pub-venue">{{ pub.venue }}{% if pub.location %}, {{ pub.location }}{% endif %} · {{ pub.year }}</span>
    <div class="pub-links">
      {% if pub.links.paper %}<a href="{{ pub.links.paper }}">paper</a>{% endif %}
      {% if pub.links.code %}<a href="{{ pub.links.code }}">code</a>{% endif %}
      {% if pub.status %}<span class="pub-status">{{ pub.status }}</span>{% endif %}
    </div>
  </li>
  {% endfor %}
</ul>
