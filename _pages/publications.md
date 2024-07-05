---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

Cooney, CR., Bright, JA., Capp, EJR., Chira, AM., Hughes, EC., Moody, CJA., Nouri, LO., Varley, ZK., Thomas, GH. (2017). <a href="https://hull-research.worktribe.com/record.jx?recordid=3267681#:~:text=Fulltext%20%2D%20Accepted%20Version-,Download,-Preview'/">Mega-evolutionary dynamics of the adaptive radiation of birds"</a>
<i>Nature</i>. 542, 344-347.

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
