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

{: .important } 
In-class activities have been cut from 12 to 6, while you can still miss two without penalty. 

{: .note } 
PA0 prompt has been revised to account for AWS account isolation. 

Click the 📺 icons below to view podcast recording. 



[Jump to the current week](#week-03){: .btn }

{% for module in site.modules %}
{{ module }}
{% endfor %}
