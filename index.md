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
PA1 due date extended to Friday, May 19th.

{: .challenge } 
Jules from Anyscale will be visiting on Thursday 5/18, and Venky from Amazon's Alexa AI team will be visiting on Thursday 5/25. There will be 2% extra credit opportunities available during each of those classes (4% total), in-person attendance is strongly encouraged.  


Click the 📺 icons below to view lecture recording. 



<!-- [Jump to the current week](#week-03){: .btn } -->

{% for module in site.modules %}
{{ module }}
{% endfor %}
