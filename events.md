---
layout: default
title: Events
---

# Upcoming Events

Join us at our events to learn, build, and connect with fellow Claude enthusiasts!

{% assign today = site.time | date: '%s' %}
{% assign upcoming_events = site.events | sort: "date" %}
{% assign past_events = site.events | sort: "date" | reverse %}

{% assign has_upcoming = false %}
{% assign has_past = false %}

<div class="events-grid">
{% for event in upcoming_events %}
  {% assign event_date = event.date | date: '%s' %}
  {% if event_date >= today %}
    {% assign has_upcoming = true %}
    {% include event-card.html event=event %}
  {% endif %}
{% endfor %}
</div>

{% unless has_upcoming %}
<div class="empty-state">
  <p>No upcoming events scheduled yet. Join our <a href="https://discord.gg/rFe8tJ88ww" target="_blank">Discord</a> to be notified when new events are announced!</p>
</div>
{% endunless %}

## Past Events

<div class="events-grid events-grid--past">
{% for event in past_events %}
  {% assign event_date = event.date | date: '%s' %}
  {% if event_date < today %}
    {% assign has_past = true %}
    {% include event-card.html event=event %}
  {% endif %}
{% endfor %}
</div>

{% unless has_past %}
<p class="text-center" style="color: var(--text-gray-3);">No past events yet.</p>
{% endunless %}
