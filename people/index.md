---
layout: page
title: The People
---

{% for page in site.pages %}
{% if page.layout == 'person' %}
<h3><a href="{{page.url}}">{{page.title}}</a> <small>{{page.description}}</small></h3>
{% endif %}
{% endfor %}

<!-- ![](https://farm9.staticflickr.com/8617/15998723793_fcd687ff1d_o_d.jpg) -->
<!-- <cite>The Wallaga Lake Aboriginal cricket team with Mr. Hockey, circa 1900. http://nla.gov.au/nla.pic-an2441655</cite> -->
