---
layout: archive
title: "Sitemap"
permalink: /sitemap/
author_profile: true
---

{% include base_path %}

A list of all the pages found on the site. For you robots out there is an [XML version]({{ base_path }}/sitemap.xml) available for digesting as well.

{% comment %} Every _pages/*.md and *.html file (about, cv, fpga, thesis, visions, controls, this page, etc.) {% endcomment %}
<h2>Pages</h2>
{% for post in site.pages %}
  {% include archive-single.html %}
{% endfor %}

{% comment %}
  Walks every collection declared in _config.yml (currently: fpga, thesis,
  visions, controls) and lists its items under its own heading.
  "posts" is always present as a built-in Jekyll collection even though this
  site has no _posts content, so it's explicitly skipped here to avoid an
  empty "Posts" heading with nothing underneath it.
{% endcomment %}
{% capture written_label %}'None'{% endcapture %}
{% for collection in site.collections %}
{% unless collection.output == false or collection.label == "posts" %}
  {% capture label %}{{ collection.label }}{% endcapture %}
  {% if label != written_label %}
  <h2>{{ label }}</h2>
  {% capture written_label %}{{ label }}{% endcapture %}
  {% endif %}
{% endunless %}
{% for post in collection.docs %}
  {% unless collection.output == false or collection.label == "posts" %}
  {% include archive-single.html %}
  {% endunless %}
{% endfor %}
{% endfor %}
