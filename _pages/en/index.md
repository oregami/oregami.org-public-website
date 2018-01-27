---
layout: default
language: en
permalink: /en
---

{% if site.posts_en.size > 0 %}
<h2 class="post-list-heading">{{ page.list_title | default: "Posts" }}</h2>
  <ul class="post-list">
  {% assign sorted = site.posts_en | sort: 'date' | reverse %}
  {% for post in sorted  %}
      <li>
        {% assign date_format = site.minima.date_format | default: "%b %-d, %Y" %}
        <span class="post-meta">{{ post.date | date: date_format }}</span>

        <h3>
          <a class="post-link" href="{{ post.url | relative_url }}">{{ post.title | escape }}</a>
        </h3>
      </li>
    {% endfor %}
  </ul>

  <p class="rss-subscribe">subscribe <a href="{{ "/feed.xml" | relative_url }}">via RSS</a></p>
{% endif %}
