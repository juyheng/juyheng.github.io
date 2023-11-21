---
layout: archive
<<<<<<< HEAD
title: "Publications"
permalink: /publications/
=======
title: "Publications-Template"
permalink: /publications-template/
>>>>>>> 37695b666520b76590fd8b4efc078dbcae4ada66
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
