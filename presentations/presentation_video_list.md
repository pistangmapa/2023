---
layout: page
title: Pista ng Mapa 2023 Video Presentations
description: Pista ng Mapa 2023 is a free and open mapping conference in the Philippines
image:
---
<a id="plenary_anchor"></a>

{: .centered-heading}

# Plenary 
{%- assign presentors = site.presentors | where: "category", "Plenary"-%}

{% for presentor in presentors %}
### {{presentor.talk_title}}
Speaker: {{presentor.name}}  
Affiliation: {{presentor.affiliation}}  
{% include recorded_vid.html link = presentor.link %}

{% endfor %}

<a id="academic_anchor"></a>

{: .centered-heading}

# Academic Track  
<p></p>
{%- assign presentors = site.presentors | where: "scid", "acad1" -%} 

{%- assign main = site.secondary_category | where: "scid", "acad1" -%}  
  
## {{main[0].title}}  

{% for presentor in presentors %}
### {{presentor.talk_title}}
Speaker: {{presentor.name}}  
Affiliation: {{presentor.affiliation}}  
{% include recorded_vid.html link = presentor.link %}

{% endfor %}

{%- assign presentors = site.presentors | where: "scid", "acad2" -%}
{%- assign main = site.secondary_category | where: "scid", "acad2" -%}

## {{main[0].title}}  

{% for presentor in presentors %}
### {{presentor.talk_title}}  
Speaker: {{presentor.name}}  
Affiliation: {{presentor.affiliation}}  
{% include recorded_vid.html link = presentor.link %}

{% endfor %}

{%- assign presentors = site.presentors | where: "scid", "acad3" -%}
{%- assign main = site.secondary_category | where: "scid", "acad3" -%}

## {{main[0].title}}  

{% for presentor in presentors %}  
### {{presentor.talk_title}}   
Speaker: {{presentor.name}}  
Affiliation: {{presentor.affiliation}}  
{% include recorded_vid.html link = presentor.link %}

{% endfor %}

<a id="general_anchor"></a>

{: .centered-heading}

# General Track  
<p></p>
{%- assign presentors = site.presentors | where: "scid", "gene1" -%}  
{%- assign main = site.secondary_category | where: "scid", "gene1" -%}  

## {{main[0].title}}  

{% for presentor in presentors %}
### {{presentor.talk_title}}  
Speaker: {{presentor.name}}  
Affiliation: {{presentor.affiliation}}    
{% include recorded_vid.html link = presentor.link %} 

{% endfor %}

{%- assign presentors = site.presentors | where: "scid", "gene2" -%}
{%- assign main = site.secondary_category | where: "scid", "gene2" -%}

## {{main[0].title}}  

{% for presentor in presentors %}
### {{presentor.talk_title}}  
Speaker: {{presentor.name}}  
Affiliation: {{presentor.affiliation}}  
{% include recorded_vid.html link = presentor.link %}

{% endfor %}

{%- assign presentors = site.presentors | where: "scid", "gene3" -%}
{%- assign main = site.secondary_category | where: "scid", "gene3" -%}

## {{main[0].title}}  

{% for presentor in presentors %}
### {{presentor.talk_title}}  
Speaker: {{presentor.name}}  
Affiliation: {{presentor.affiliation}}   
{% include recorded_vid.html link = presentor.link %} 

{% endfor %}

<a id="lightning_anchor"></a>

{: .centered-heading}

# Lightning Talks  
<p></p>
{%- assign presentors = site.presentors | where: "scid", "light1" -%}   
{%- assign main = site.secondary_category | where: "scid", "light1" -%}  

## {{main[0].title}}  

{% for presentor in presentors %}
### {{presentor.talk_title}}  
Speaker: {{presentor.name}}  
Affiliation: {{presentor.affiliation}}  
{% include recorded_vid.html link = presentor.link %}

{% endfor %}

{%- assign presentors = site.presentors | where: "scid", "light2" -%}
{%- assign main = site.secondary_category | where: "scid", "light2" -%}

## {{main[0].title}}  

{% for presentor in presentors %}
### {{presentor.talk_title}}  
Speaker: {{presentor.name}}  
Affiliation: {{presentor.affiliation}}  
{% include recorded_vid.html link = presentor.link %} 

{% endfor %}

{%- assign presentors = site.presentors | where: "scid", "light3" -%}
{%- assign main = site.secondary_category | where: "scid", "light3" -%}

## {{main[0].title}}  

{% for presentor in presentors %}
### {{presentor.talk_title}}  
Speaker: {{presentor.name}}  
Affiliation: {{presentor.affiliation}}  
{% include recorded_vid.html link = presentor.link %}

{% endfor %}