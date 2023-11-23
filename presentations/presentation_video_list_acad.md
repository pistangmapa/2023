---
layout: page
title: Pista ng Mapa 2023 Academic Video Presentations
description: Pista ng Mapa 2023 is a free and open mapping conference in the Philippines
image:
---

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