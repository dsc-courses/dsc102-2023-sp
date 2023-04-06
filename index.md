---
layout: home
title: Home
nav_exclude: false
nav_order: 1
---

# {{ site.tagline }}
{: .mb-2 }
{{ site.description }}
{: .fs-6 .fw-300 }

{{ site.staffersnobio }}

{: .note } 
Discussions/Lab sessions will be held Tuesdays 7:00pm-7:50pm in MANDE B-210.

Click the 📺 icons below to view podcast recording. 



[Jump to the current week](#week-01){: .btn }

{% for module in site.modules %}
{{ module }}
{% endfor %}
