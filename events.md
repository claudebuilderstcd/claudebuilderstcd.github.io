---
layout: default
title: Events
---

# Upcoming Events

Join us at our events to learn, build, and connect with fellow Claude enthusiasts!

{% assign today = 'now' | date: '%Y-%m-%d' %}
{% assign upcoming_events = site.events | where_exp: "event", "event.date >= today" | sort: "date" %}
{% assign past_events = site.events | where_exp: "event", "event.date < today" | sort: "date" | reverse %}

{% if upcoming_events.size > 0 %}
<div class="events-grid">
  {% for event in upcoming_events %}
    {% include event-card.html event=event %}
  {% endfor %}
</div>
{% else %}
<div class="empty-state">
  <p>No upcoming events scheduled yet. Join our <a href="https://discord.gg/rFe8tJ88ww" target="_blank">Discord</a> to be notified when new events are announced!</p>
</div>
{% endif %}

{% if past_events.size > 0 %}
## Past Events

<div class="events-grid events-grid--past">
  {% for event in past_events %}
    {% include event-card.html event=event %}
  {% endfor %}
</div>
{% endif %}
