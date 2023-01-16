---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
Valenti, V.L., E.C. Carcelen, K. Lange, N.J. Russo, and B. Chapman. 2020. Leveraging Google Earth Engine user interface for semi-automated wetland classification in the Great Lakes Basin at 10 m with optical and radar geospatial datasets. IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing 13: 6008-6018. 

Robertson, M.W., N.J. Russo, S.J. McInnes, B. Goffinet, and J.E. Jiménez. 2020. Potential dispersal of tardigrades by birds through endozoochory: evidence from sub-Antarctic White-bellied Seedsnipe (Attagis malouinus). Polar Biology 43: 899–902.

Russo, N.J., M.W. Robertson, R. MacKenzie, B. Goffinet, and J. Jiménez. 2020. Evidence of targeted consumption of mosses by birds in sub-Antarctic South America. Austral Ecology 45: 399-403. 

Russo, N.J., C.S. Elphick, N.P. Havill, and M.W. Tingley. 2019. Spring bird migration as a dispersal mechanism for the hemlock woolly adelgid. Biological Invasions 5: 1585-1599. 

Russo, N.J., C.A.S.-J. Cheah, and M.W. Tingley. 2016. Experimental evidence for branch-to-bird transfer as a mechanism for avian dispersal of the hemlock woolly adelgid (Hemiptera: Adelgidae). Environmental Entomology 45: 1107-1114.

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
