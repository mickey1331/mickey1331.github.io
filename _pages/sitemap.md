---
layout: archive
title: "Sitemap"
permalink: /sitemap/
lang: en
lang_url: /zh/sitemap/
author_profile: true
---

{% include base_path %}

A list of all the pages on the site (English version). There is an [XML version]({{ base_path }}/sitemap.xml) available for crawlers.

<h2>Pages</h2>
{% for post in site.pages %}
  {% assign post_lang = post.lang | default: 'en' %}
  {% if post_lang != 'en' %}{% continue %}{% endif %}
  {% include archive-single.html %}
{% endfor %}
