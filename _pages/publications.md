---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

Lasted Update: 25th June 2023 [中文](publications-zh)

None of the educational programmes that have come along the way have requirements for publications, **but** I know that this is not a reason for me to hold off on high impact factor publications. Instead, I'm grateful to BNU for giving me a **good academic foundation**, and I'm grateful to the University of Leeds for the programme requirements that allowed me to **write a large number of scientific papers in one year**. These have given me the confidence to take on the challenge of publishing journals. Perhaps all that is needed is **a light in the darkness of the night** and I will come in the direction of guidance.

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
