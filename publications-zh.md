---
layout: archive
title: "刊物"
permalink: /publications/
author_profile: true
---

一路而来的教育方案都没有对刊物有要求，但我知道这并非是我暂无高影响因子刊物的理由。反而我很感激北京师范大学，因为让我有了一个很好的学术基础；我很感谢利兹大学的课程要求，让我在一年内写作了大量的科研论文。这些都让我有信心接受发表刊物的挑战。或许需要的只是一盏黑夜中的灯，我会向指引的方向而来。

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
