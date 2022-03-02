---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---


|<img src="../images/figs/cnlp.png" alt="cnlp" width="300"/>  |   Son N. Tran, Compositional Neural Logic Programming. Proceedings of the Thirtieth International Joint Conference on Artificial Intelligence, 3059–3066. <br> [pdf](https://www.ijcai.org/proceedings/2021/0421.pdf)|
|<img src="../images/figs/dln.png" alt="cnlp" width="300"/>  |   Son N. Tran and Artur d'Avila Garcez, Deep Logic Network: Inserting and Extracting Knowledge From Deep Belief Networks. IEEE Transaction of Neural Networks and Learning Systems. <br> [pdf](https://ieeexplore.ieee.org/document/7738566)|


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.research reversed %}
  {% include archive-single.html %}
{% endfor %}
