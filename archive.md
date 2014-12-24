---
layout: page
title: Archive
---

{% for post in site.posts %}
{% unless post.link %}
<section class="date-section">
{% capture currentdate %}{{post.date | date: "%B, %Y"}}{% endcapture %}
{% if currentdate != thedate %}
<h3 class="date">{{ currentdate }}</h3>
{% capture thedate %}{{currentdate}}{% endcapture %}
{% endif %}
<article class="post-preview">
<h3 class="post-title"><a href="{% if post.link %}{{ post.link }}{% else %}{{ post.url }}{% endif %}">{{ post.title }}</a></h3>
</article>
</section>
{% endunless %}
{% endfor %}
