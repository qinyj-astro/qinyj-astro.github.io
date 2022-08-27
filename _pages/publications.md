---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

Peer-reviewed papers: [ADS Library](https://ui.adsabs.harvard.edu/public-libraries/n0vGfGgtTjaQGr4j8Teo-g) and [ORCID](https://orcid.org/0000-0003-3658-6026)

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
