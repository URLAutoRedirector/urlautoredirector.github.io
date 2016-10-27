---
layout: page
title: What's New
inline-title: Changelog
permalink: changelog.html
---
{% for change in site.data.changelog %}
  <h3 id="changelog-{{ change.version }}">
    Version <a href="#changelog-{{ change.version }}">{{ change.version }}</a>
  </h3>
  <ul>
    {% for log in change.changes %}
      <li>
        {{ log.text }}
        {% if log.issue != nil %}
          <a href="https://github.com/UrlAutoRedirector/UrlAutoRedirector/issues/{{ log.issue }}">#{{ log.issue }}</a>
        {% endif %}
      </li>
    {% endfor %}
  </ul>
{% endfor %}