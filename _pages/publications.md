---
layout: archive
title: "Research"
permalink: /publications/
author_profile: true
---

Articles Under Review:

Xie, P., Kim, E., Lam, S., Reza, S. “Herding in NFT Auction: The Role of Visual Complexity and Familiarity.”, 2nd round review at International Journal of Research in Marketing.

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
