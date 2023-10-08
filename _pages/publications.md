---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---


Current Employment
======
Northwestern University, Evanston, IL
- Postdoctoral Fellow, Department of Electrical Engineering and Computer Science, 2022-Present.

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
