---
layout: archive
permalink: /publications/
title: "Publications"
author_profile: true
---
<p>
This section lists my publications, including journal articles, conference papers, and preprints related to graph theory, combinatorial optimization, and network systems.
</p>

<p><strong>Indexing profiles</strong></p>
<ul>
  <li>
    <strong>Mathematics:</strong>
    <a href="https://mathscinet-ams-org.proxy.rubens.ens.fr/mathscinet/MRAuthorID/1533482">MathSciNet (AMS)</a>,
    <a href="https://zbmath.org/authors/?q=ai:li.shu">zbMATH Open</a>
  </li>
  <li>
    <strong>Computer Science:</strong>
    <a href="https://dblp.org/pid/66/6852-6">dblp</a>,
    <a href="https://openreview.net/profile?id=%7EShu_Li12">OpenReview</a>
  </li>
</ul>

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
