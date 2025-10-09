---
layout: archive
title: "Presentations & Posters"
permalink: /talks/
author_profile: true
---
<p>
This section presents my recent academic talks, conference presentations, and posters, covering topics in graph theory, combinatorial optimization, and network analysis.
</p>

<h2>Conferences & Workshops</h2>
  {% for post in site.talks reversed %} 
    {% if post.type == 'Talk' %} 
      {% include archive-single-talks.html %}
    {% endif %}
  {% endfor %}

<h2>Seminars</h2>
{% for post in site.talks reversed %}
  {% if post.type == 'Seminar' %} 
    {% include archive-single-talks.html %}
  {% endif %}
{% endfor %}
