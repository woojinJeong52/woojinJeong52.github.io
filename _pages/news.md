---
layout: page
title: News
permalink: /news/
nav: true
nav_order: 99
---

<div class="news">
  {% if site.news != blank %}
    {% assign news_size = site.news | size %}
    <div class="table-responsive">
      <table class="table table-sm table-borderless">
        {% assign news = site.news | reverse %}
        {% for item in news %}
          <tr>
            <th scope="row" style="width: 20%">{{ item.date | date: '%b %d, %Y' }}</th>
            <td>
              {% if item.inline %}
                {{ item.content | emojify }}
              {% else %}
                <a class="news-title" href="{{ item.url | relative_url }}">{{ item.title }}</a>
                {% if item.content and item.content != '' %}
                  <div style="margin-top: 0.8rem">{{ item.content }}</div>
                {% endif %}
              {% endif %}
            </td>
          </tr>
        {% endfor %}
      </table>
    </div>
  {% else %}
    <p>No news so far...</p>
  {% endif %}
</div>
