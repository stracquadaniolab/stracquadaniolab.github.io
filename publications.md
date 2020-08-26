---
title: Selected publications
layout: default
---
A selected list of publications is provided below. The complete list of publications is available on [Google Scholar](https://goo.gl/faI6XG).  

## Peer-reviewed articles
<OL>
{% for paper in site.data.publications %}
  {% if paper.ENTRYTYPE == 'article' %}
<li><a href="http://dx.doi.org/{{ paper.doi }}" name="{{paper.ID}}">{{ paper.title }}</a>.  
{{ paper.author | replace: '*', '<sup>1</sup>'| replace: '^', '<sup>3</sup>'| replace: 'Stracquadanio', '<b>Stracquadanio</b>' }}, {{ paper.journal }}, {{ paper.year }}.</li>
  {% endif %}
{% endfor %}
</ol>

## Preprints
<OL>
{% for paper in site.data.publications %}
  {% if paper.ENTRYTYPE == 'preprint' %}
<li><a href="http://dx.doi.org/{{ paper.doi }}" name="{{paper.ID}}">{{ paper.title }}</a>.  
{{ paper.author | replace: '*', '<sup>1</sup>'| replace: '^', '<sup>3</sup>'| replace: 'Stracquadanio', '<b>Stracquadanio</b>' }}, {{ paper.journal }}, {{ paper.year }}.</li>
  {% endif %}
{% endfor %}
</ol>

## Books and contributed chapters
<ul>
{% for paper in site.data.publications %}
  {% if paper.ENTRYTYPE == 'book' %}
  <li><a href="http://dx.doi.org/{{ paper.doi }}">{{ paper.title }}</a>.  
    {{ paper.author }}, {{ paper.journal }}, {{ paper.year }}.</li>  
  {% endif %}
{% endfor %}
</ul>