---
layout: single
title: Full List of Publications
author_profile: false
---

<div class="pub">
{% for item in site.data.pubs.pubs reversed %}
  {% capture pub_id %}{{ item[0] }}{% endcapture %}
  {% include pub_item id=pub_id %}
{% endfor %}
</div>
