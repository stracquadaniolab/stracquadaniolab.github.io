---
title: Publications
layout: default
---

##### Journal articles

{% for paper in site.data.publications %}
*  [{{ paper.title }}](http://dx.doi.org/{{ paper.doi }}).  
   {{ paper.author | replace: 'Stracquadanio', '**Stracquadanio**' }}  
   *{{ paper.journal }}, {{ paper.year }}.*
{% endfor %}
