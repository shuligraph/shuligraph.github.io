---
layout: archive
title: "Presentations & Posters"
permalink: /talks/
author_profile: true
---

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
