---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
author.googlescholar: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="https://scholar.google.co.uk/citations?user=wNaWUWEAAAAJ&hl=en">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
