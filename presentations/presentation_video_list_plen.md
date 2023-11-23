---
layout: page
title: Pista ng Mapa 2023 Plenary Video Presentations
description: Pista ng Mapa 2023 is a free and open mapping conference in the Philippines
image:
---

# Plenary 
{%- assign presentors = site.presentors | where: "category", "Plenary"-%}

{% for presentor in presentors %}
### {{presentor.talk_title}}
Speaker: {{presentor.name}}  
Affiliation: {{presentor.affiliation}}  
{% include recorded_vid.html link = presentor.link %}

{% endfor %}