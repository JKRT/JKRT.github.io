---
layout: archive
title: "Sitemap"
permalink: /sitemap/
author_profile: true
---

{% include base_path %}

All pages on this site. An [XML version]({{ base_path }}/sitemap.xml) is also available.

{% for post in site.pages %}{% unless post.sitemap == false or post.title == nil %}
  {% include archive-single.html %}
{% endunless %}{% endfor %}
