---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

something
{% for pub in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}