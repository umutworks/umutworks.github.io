---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
{% include base_path %}

**All my papers are available at Google Scholar. Here, I also publish preprint versions. Click the paper name to access!**

[**Google Scholar**](https://scholar.google.com/citations?user=UtkbGQcAAAAJ&hl=en)

{% for post in site.publications reversed %}

    {% include archive-single.html %}

{% endfor %}
