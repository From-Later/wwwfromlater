---
title: "Views"
layout: default
left_sticky_content: |
  # [ Views ] from later
  Futures research and inquiry through scenarios, songs, design fictions, speculations, lexicons, prototypes, and illustrations.
---

## Scanning the extreme present. Drafting possible futures.

**[ Views ] from later** catalogues our ongoing work in:

{: .highlight-block }

- Observing, understanding, and analyzing change
- Locating critical territories for focused research and exploration
- Generating possibilites and provoking new thinking
- Drafting futures, developing scenarios, and imagining new pathways for transformation

{% for entry in site.data.navigation %}
{% capture fullurl %}{{ site.baseurl }}{{ entry.url }}{% endcapture %}
{% if entry.title contains "Views" %}
{% assign views = entry %}
{% break %}
{% endif %}
{% endfor %}
{% for subfolder in views.subfolders %}
<strong>{{ subfolder.title }}</strong>

<ul>
{% for item in subfolder.subfolderitems %}

<li>
<a href="{{item.url}}">{{item.title}}</a>
</li>
{% endfor %}
</ul>
{% endfor %}
