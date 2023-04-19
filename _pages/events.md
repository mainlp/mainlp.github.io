---
layout: page
permalink: /events/
title: Events
description: 
nav: true
nav_order: 5
---

<!-- pages/events.md -->
<!-- events are sorted by filename (reverse order) -->
<div class="events">
  {%- for event in site.events reversed -%}
    <div class="event">
	  {% include events.html %}
    </div>
  {%- endfor %}
</div>