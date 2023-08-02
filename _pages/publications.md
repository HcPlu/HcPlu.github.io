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
  <p>{{ index }}. {{post.citation}}</p>
{% endfor %}
