---
layout: default
title: People
permalink: /people/
---

## Principal Investigator
<div class="row">
    <div class="two columns">
        <img class="portrait" src="/images/gspic.jpg"/>
    </div>
    <div class="ten columns">
        <h3>Giovanni Stracquadanio, PhD FHEA</h3>
        <p>
            <b>Senior Lecturer in Synthetic Biology</b><br/>
            <b>Co-Director of the Edinburgh Genome Foundry</b><br/>
            School of Biological Sciences, Michael Swann Building, Room 2.35, The King's Buildings<br/>
            The University of Edinburgh, Edinburgh, EH9 3BF<br/>
            email: giovanni (dot) stracquadanio (at) ed (dot) ac (dot) uk  
        </p>
    </div>
</div>

## Lab members

<div class="row">
    {% for people in site.data.people %}
        {% if people.role == 'phd' %}
        <div class="row member">
            <div class="two columns">
                <img class="portrait" src="{{people.pic}}"/>
            </div>
            <div class="ten columns">
                <h3>{{people.name}}</h3>
                <p>
                <i>PhD student</i><br/>
                Research area: {{people.area}}
                </p>
            </div>
        </div>
        {% endif %}
    {% endfor %}
    {% for people in site.data.people %}
        {% if people.role == 'ug' %}
        <div class="row member">
            <div class="two columns">
                <img class="portrait" src="{{people.pic}}"/>
            </div>
            <div class="ten columns">
                <h3>{{people.name}}</h3>
                <p>
                <i>Hons. Student</i><br/>
                Research area: {{people.area}}
                </p>
            </div>
        </div>
        {% endif %}
    {% endfor %}
</div>
<br>

## Alumni
<div>
    <ul>
    {% for people in site.data.people %}
        {% if people.role == 'alumni' %}
            <li>{{people.name}}; {{people.area}}</li>
        {% endif %}
    {% endfor %}
    </ul>
</div>

## Postdoctoral and Doctoral students
Positions will be posted on this page and on institutional websites as soon as they become available. However, if you are eligible for a funding scheme or a fellowship and you want to join the lab, please send an email to Giovanni Stracquadanio attaching the following documents:  

*  Cover letter, addressing how you fit with the strategic research areas of the lab, such as: synthetic biology, next generation sequencing, GWAS, network biology;
*  Curriculum vitae.

##### Funding opportunities
* [EMBO Fellowships](http://www.embo.org/funding-awards/fellowships)
* [Marie Curie Fellowships](http://ec.europa.eu/research/mariecurieactions/about/individual-fellowships_en)
* [Newton Fellowships](http://newtonfellowships.org/the-fellowships/)
* [Wellcome Trust Fellowships](https://wellcome.ac.uk/funding/sir-henry-wellcome-postdoctoral-fellowships)
* [Leverhulme Trust Fellowships](https://www.leverhulme.ac.uk/funding/grant-schemes/early-career-fellowships)
