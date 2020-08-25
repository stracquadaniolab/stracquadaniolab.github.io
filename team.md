---
layout: default
title: Team
permalink: /team/
---

<div class="row p-4 mb-4">
    <div class="col-2">
        <img class="rounded-circle" src="/images/gspic.jpg" width="75%"/>
    </div>
    <div class="col-10">
        <h5>Giovanni Stracquadanio, PhD FHEA</h5>
        <p>
            <b>Senior Lecturer in Synthetic Biology</b>; 
            <b>Co-Director of the Edinburgh Genome Foundry</b><br/>
            School of Biological Sciences, Michael Swann Building, Room 2.35, The King's Buildings<br/>
            The University of Edinburgh, Edinburgh, EH9 3BF<br/>
            email: giovanni (dot) stracquadanio (at) ed (dot) ac (dot) uk  
        </p>
    </div>
</div>

### Lab members

<div class="row p-4 mb-4">
{% for people in site.data.people %}
{% if people.role != 'alumni' %}
    <div class="col-1 mb-4">
        <img class="rounded-circle rounded-sm" src="{{people.pic}}" width="100%" />
    </div>
    <div class="col-5 mb-4">
        <b>{{people.name}}</b><br/>
        Position: <i>{{people.role}}</i><br/>
        Research area: <i>{{people.area}}</i>
    </div>
{% endif %}
{% endfor %}
</div>

### Recent alumni
<div>
    <ul>
    {% for people in site.data.people %}
        {% if people.role == 'alumni' %}
            <li>{{people.name}}, {{people.affiliation}}; {{people.area}}.</li>
        {% endif %}
    {% endfor %}
    </ul>
</div>


