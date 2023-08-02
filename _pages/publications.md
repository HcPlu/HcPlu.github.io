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
  <p>{{ index }}.     {% assign citation_parts = post.citation | split: ', ' %}
  {% for part in citation_parts %}
    {% if part contains "Chengpeng Hu" %}
      {% if part contains "and Chengpeng Hu" %}
        {% assign authors = part | split: ' and ' %}
        {% for author in authors %}
          {% if author == "Chengpeng Hu" %}
            <strong>{{ author }}</strong>{% unless forloop.last %}, {% endunless %}
          {% else %}
            {{ author }}{% unless forloop.last %}, {% endunless %}
          {% endif %}
        {% endfor %}
      {% else %}
        <strong>{{ part }}</strong>{% unless forloop.last %}, {% endunless %}
      {% endif %}
    {% else %}
      {{ part }}{% unless forloop.last %}, {% endunless %}
    {% endif %}
  {% endfor %} <a  href="{{ post.paperurl }}"><u>[pdf]</u></a></p>
{% endfor %}
