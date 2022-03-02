---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---


<img src="../images/figs/cnlp.png" alt="cnlp" width="200"/>  |   Son N. Tran, Compositional Neural Logic Programming. Proceedings of the Thirtieth International Joint Conference on Artificial Intelligence, 3059–3066.

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.research reversed %}
  {% include archive-single.html %}
{% endfor %}
