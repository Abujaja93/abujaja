---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

* Zakaria, H., Obeng, F. K., Quainoo, A. K., **Abujaja, A. M.** (2022). Prospects ad Constraints faced y Smallholder Farmers in the Cultivation of GM crops: A Case Study from Northern Ghana. Africa Journal of Agricultural Research. 18(3): 221-230.

* Amuriyaga, I. D., Hudu, Z., and **Abujaja, A. M.** (2018). Effectiveness of Project Method of Teaching on Agricultural Knowledge and Skills Acquisition among Agricultural Science Students of Awe Senior High School in the Upper East Region, Ghana. World Journal of Educational Research and Reviews. 4(1): 062-075.

* Amuriyaga, I. D., **Abujaja, A. M.**, Hudu, Z. (2018). Organizing Project Method of Teaching for Effective Agricultural Knowledge and Skills Acquisition: Comparison of Individual and Group Student Project. Journal of Education and Practice. 9 (23): 50-55.  



{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
