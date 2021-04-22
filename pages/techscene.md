---
layout: page
show_meta: false
title: "Linki do spisu tresci"
subheadline: "Polish tech comm scene"
header:
   image_fullwidth: "header_unsplash_5.jpg"
permalink: "/techscene/"
---
<ul>
    {% for post in site.categories.techscene %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>