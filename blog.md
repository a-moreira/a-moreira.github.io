---
layout: default.liquid
---
{% for post in collections.posts.pages %}

[{{ post.title }}]({{ post.permalink }})
{% endfor %}

<a href="https://creativecommons.org/licenses/by/4.0/"><img src="assets/by.png" style="width:5%; height:auto" /></a>

