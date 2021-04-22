---
layout: page
show_meta: false
title: "Test"
subheadline: "Testowo"
header:
   image_fullwidth: "header_unsplash_12.jpg"
permalink: "/design/"
---
<ul>
    {% for page in site.tags.phase %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ page.url }}">{{ page.title }}</a></li>
    {% endfor %}
</ul>