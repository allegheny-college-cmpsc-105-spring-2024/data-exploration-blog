---
layout: default
title: My Data Explorations
permalink: /explorations
nav: true
---
{% for lab in site.explorations %}
    <div class="general">
        <h2><a href="{{ lab.permalink }}">{{ lab.title }}</a></h2>
    </div>
{% endfor %}