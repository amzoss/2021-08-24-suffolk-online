---
layout: slides
title: SQL slides
description: A presentation slide for how to use reveal.js in Jekyll
theme: white
transition: slide
permalink: /sql/
---
{% for slide in site.sql %}
<section data-markdown>
    {{ slide.content }}
</section>
{% endfor %}
