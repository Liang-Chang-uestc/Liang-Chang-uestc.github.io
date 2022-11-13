---
layout: archive
title: "Publications ([Google Scholar](https://scholar.google.com/citations?user=5pWnfJcAAAAJ))"
permalink: /publications/
author_profile: true
---

<br>
# Journal papers

## 2022

[Jxx] <b>[ADAS: A High Computational Utilization Dynamic Reconfigurable Hardware Accelerator for Super Resolution] (../publications/TRETS2022)</b><br>
<b>Liang Chang</b>, Xin Zhao, Jun Zhou. 
ACM Trans. Reconfigurable Technol. Syst. 2022. 

# Conference papers

## 2022
[Jxx] <b>[ADAS: A High Computational Utilization Dynamic Reconfigurable Hardware Accelerator for Super Resolution] (../publications/FPT2022)</b><br>
<b>Liang Chang</b>, Xin Zhao, Jun Zhou. 
IEEE International Conference on Field Programmable Technology, Journal Track, 2022, Hong Kong SAR. 



{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
