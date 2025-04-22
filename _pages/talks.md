---
layout: archive
title: "Talks"
permalink: /talks/
author_profile: true
---

<h2>Conferences</h2>
  {% for post in site.talks reversed %} 
    {% if post.type == 'Talk' %} 
      {% include archive-single-talk.html %} 
    {% endif %}
  {% endfor %}

<h2>Seminars</h2>
{% for post in site.talks reversed %}
  {% if post.type == 'Seminar' %} 
    {% include archive-single-talk.html %}
  {% endif %}
{% endfor %}
