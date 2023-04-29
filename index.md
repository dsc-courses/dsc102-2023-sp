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
PA1 release moved to 4/30 

{: .note } 
Revised slides for 4/25 to more accurately bucket some AWS services within PaaS and SaaS.

{: .challenge } 
Beat the 255 second best runtime on PA0 for 2% extra credit! Must be reproducible, and beat by 10 seconds for eligibility, with correct results on test datasets. Can only be won once per team. 

Click the 📺 icons below to view lecture recording. 



<!-- [Jump to the current week](#week-03){: .btn } -->

{% for module in site.modules %}
{{ module }}
{% endfor %}
