---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

You can find my articles on <a href="https://scholar.google.com/citations?hl=en&user=1459xkQAAAAJ" target="_blank"><strong>my Google Scholar profile</strong></a>.

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
