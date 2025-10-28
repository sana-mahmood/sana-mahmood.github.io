---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% for pub in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}