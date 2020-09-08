---
title: "Views"
layout: default
left_sticky_content: |
  # [ Views ] from later
  Futures research and inquiry through scenarios, songs, design fictions, speculations, lexicons, prototypes, and illustrations at the foresight studio.  
  > **fore-**  
  designating the earliest time   
  **sight**    
  perception on a direct and immediate level; the faculty or act of understanding  
  **studio**   
  from Italian studio “room for study”, from Latin studium “application of the mind to the acquisition of knowledge, intensive reading, and contemplation”
---

## Drafting possible futures

As a foresight studio, our practice devotes time and space to developing novel futures perspectives.

Our work is a constant and overlapping cycle of interdependent activities: scanning the extreme present for signals of change; defining new territories for focused research; mapping consequences and imagining possible futures; and critically interpreting our research through artistic processes, speculative prototypes, and literary artifacts.

Our research projects are catalogued here as generative resources for new cultural and design imaginaries.

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
