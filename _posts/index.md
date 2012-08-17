---
layout: home
title: Ariadne Diagnostics
---

##Mission

* To improve the standard of care for patients through the development of targeted diagnostics
* To apply the power of 21<sup>st</sup> century Bioinformatics to identify targeted and integrated biomarker panels for companion diagnostic development</li>
* To utilize the principles of translational medicine to continually improve existing and future diagnostic tests

{% for post in site.posts %}
     <div class="hero-unit">
       <a href="{{ post.url }}">{{ post.title }}</a>
     </div>
{% endfor %}
