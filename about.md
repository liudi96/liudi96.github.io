---
layout: page
title: "关于"
permalink: about.html
image: /public/images/redflag.jpg
color: '#f44336'
sequence: 9
---


{% comment %}
  This inserts the "about" photo and text from `_config.yml`.
  You can edit it there (jekyll needs restart!) or remove it and provide your own photo/text.
  Don't forget to add the `me` class to the photo, like this: `![alt](src){:.me}`.
{% endcomment %}

{% if site.author.photo %}
  ![{{site.author.name}}]({{site.author.photo}}){:.me}
{% endif %}


我是<u>刘的</u>


