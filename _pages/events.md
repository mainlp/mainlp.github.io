---
layout: page
permalink: /events/
title: Events
description: 
nav: true
nav_order: 5
---

<!-- pages/events.md -->
<div class="events">
	{%- for event in site.events -%}
	  {% include events.html %}
	{%- endfor %}
</div>
