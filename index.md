---
layout: home
title: Ariadne Diagnostics
---

Ariadne Diagnostics, LLC is a molecular diagnostic company focused on discovery and development of companion diagnostic tests in areas of oncology and rare neuromuscular/neurodegenerative diseases.

##Mission

* To advance personalized medicine and facilitate pharmaceutical decisions by creating tests based on novel insights into mechanisms of disease
* To combine clinical expertise and knowledge-driven informatics to uncover disease mechanisms from molecular patient data

{% for post in site.posts %}
     <div class="hero-unit">
       <a href="{{ post.url }}">{{ post.title }}</a>
     </div>
{% endfor %}
