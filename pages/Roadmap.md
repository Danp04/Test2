---
layout: page
subheadline: "Phase"
title: "Development phases"
teaser: "Follow the steps below."
header:
   image_fullwidth: "header_unsplash_5.jpg"
permalink: "/Roadmap/"
---
<ul>
    {% for post in site.tags.phase %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>