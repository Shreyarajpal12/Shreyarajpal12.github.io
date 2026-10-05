---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
description: "Publications by Shreya Rajpal on trustworthy AI, neuro-symbolic spatial reasoning, language models, video understanding, and production recommender systems, including EMNLP 2026 work."
---


{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on my <a href="{{site.author.googlescholar}}">Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}
{% for post in site.publications reversed %}
  {% include short-pub.html %}
{% endfor %}
