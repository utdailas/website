---
title: Events
nav:
  order: 4
  tooltip: Lab events and activities
---

# {% include icon.html icon="fa-solid fa-calendar" %}Events

{% include section.html %}

## Upcoming Events

<div class="events-list">
{% include list.html data="events" component="event" %}
</div>

{% include section.html %}

## Past Events

<div class="events-list">
{% include list.html data="events" component="event" filters="group: past" %}
</div>