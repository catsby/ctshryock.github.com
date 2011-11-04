---
layout: default
image: magic_tree.JPG
name: magic
---


{% assign first_post = site.posts.last %}
<img src="{{site.url}}/images/{{ first_post.image }}" title="{{ site.post.first.name }}" />

