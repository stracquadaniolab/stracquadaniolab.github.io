---
title: Publications
layout: default
---
A selected list of publications is provided below. The complete list of my publications is available on [Google Scholar](https://goo.gl/faI6XG).  
<sup>1</sup> : co-first, equally contributing author.  
<sup>2</sup> : co-corresponding author.  
<sup>3</sup> : author listed in alphabetical order.

##### Journal articles
{% for paper in site.data.publications %}
  {% if paper.ENTRYTYPE == 'article' %}
* [{{ paper.title }}](http://dx.doi.org/{{ paper.doi }}).  
{{ paper.author | replace: '*', '<sup>1</sup>'| replace: '^', '<sup>3</sup>'| replace: 'Stracquadanio', '**Stracquadanio**' }}, *{{ paper.journal }}, {{ paper.year }}.*   
  {% endif %}
{% endfor %}

##### Books and contributed chapters
{% for paper in site.data.publications %}
  {% if paper.ENTRYTYPE == 'book' %}
*  [{{ paper.title }}](http://dx.doi.org/{{ paper.doi }}).  
    {{ paper.author }}, *{{ paper.journal }}, {{ paper.year }}.*  
  {% endif %}
{% endfor %}

##### Conference proceedings
{% for paper in site.data.publications %}
  {% if paper.ENTRYTYPE == 'conference' %}
*  [{{ paper.title }}](http://dx.doi.org/{{ paper.doi }}).  
{{ paper.author | replace: '*', '<sup>1</sup>'| replace: '^', '<sup>3</sup>'| replace: 'Stracquadanio', '**Stracquadanio**' }}, *{{ paper.journal }}, {{ paper.year }}.*  
  {% endif %}
{% endfor %}
