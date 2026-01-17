---
layout: default
title: News
---

# News & Announcements

Stay updated with the latest from TCD Claude Builder Club.

{% assign all_news = site.news | sort: "date" | reverse %}

{% if all_news.size > 0 %}
<div class="news-list">
  {% for news in all_news %}
    {% include news-card.html news=news %}
  {% endfor %}
</div>
{% else %}
<div class="empty-state">
  <p>No news yet. Check back soon for updates!</p>
</div>
{% endif %}
