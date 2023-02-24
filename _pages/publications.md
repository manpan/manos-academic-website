---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

* [Profile](https://scholar.google.com/citations?user={{ site.data.scholar.id }}), {{ site.data.scholar.citations }}


List of my peer-reviewed publications, presented in chronological order along with
[JCR](https://clarivate.com/webofsciencegroup/solutions/journal-citation-reports/), [CiteScore](https://www.scopus.com/authredirect.uri?txGid=ba9770c620c7d5b715fd72c9fd1d2f5d&code=mgQ4ISuu_SZoRtaw_jQp3aJiHFyZveTKNvMerqJs&state=autoLogin%7CtxId%3DDFD11B40110D74A323A75413629FB5D2.i-0ce250737914d0065%3A2) and [Core ranking](https://www.core.edu.au/conference-portal) scores.  

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}


