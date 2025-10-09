---
layout: archive
permalink: /publications/
title: "Publications"
author_profile: true
---
<p>
This section lists my publications, including journal articles, conference papers, and preprints related to graph theory, combinatorial optimization, and network systems.
</p>

<h2>Journals</h2>
  {% for post in site.publications reversed %} 
    {% if post.pubtype == 'journal' %} 
      {% include archive-single-publish.html %} 
    {% endif %}
  {% endfor %}

<h2>Conferences</h2>
{% for post in site.publications reversed %} 
{% if post.pubtype == 'conference' %} 
{% include archive-single-publish.html %} 
{% endif %}
{% endfor %}

<h2>Preprints</h2>
  {% for post in site.publications reversed %} 
    {% if post.pubtype == 'preprint' %} 
      {% include archive-single-publish.html %} 
    {% endif %}
  {% endfor %}

<h2>Thesis</h2>
  {% for post in site.publications reversed %} 
    {% if post.pubtype == 'thesis' %} 
      {% include archive-single-publish.html %} 
    {% endif %}
  {% endfor %}
