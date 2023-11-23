---
layout: page
title: Pista ng Mapa 2023 General Video Presentations
description: Pista ng Mapa 2023 is a free and open mapping conference in the Philippines
image:
---

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