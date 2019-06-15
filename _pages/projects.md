---
layout: archive
permalink: /projects/
title: "My projects"
author_profile: true
header:
    image: "/images/cat.jpg"
---


{% include group-by-array collection=site.posts field="tags" %}

{% for post in posts %}
    {% include archive-single.html %}
{% endfor %}
