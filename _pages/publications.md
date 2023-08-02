---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% assign total_items = site.publications.size %}
{% for post in site.publications reversed %}
    {% assign index = total_items | minus: forloop.index0 %} 
  <p>{{ index }}. {% assign citation_parts = post.citation | split: "." %}
  {% for part in citation_parts %}
    {% if part contains ".”" %}
      {% assign authors_part = part | split: "., " %}
      {% for author_part in authors_part %}
        {% assign authors = author_part | split: ", " %}
        {% for author in authors %}
          {% assign author_name = author | split: " " %}
          {% for name in author_name %}
            {% if name == "Chengpeng" and author_name contains "Hu" %}
              <strong>{{ author }}</strong>
            {% else %}
              {{ author }}
            {% endif %}
            {% unless forloop.last %} {% endunless %}
          {% endfor %}
          {% unless forloop.last %}, {% endunless %}
        {% endfor %}
      {% endfor %}
    {% else %}
      {{ part }}.
    {% endif %}
  {% endfor %} <a  href="{{ post.paperurl }}"><u>[pdf]</u></a></p>
{% endfor %}
