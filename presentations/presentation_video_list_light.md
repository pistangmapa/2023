---
layout: page
title: Pista ng Mapa 2023 Lightning Video Presentations
description: Pista ng Mapa 2023 is a free and open mapping conference in the Philippines
image:
---

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