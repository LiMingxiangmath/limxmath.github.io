---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{[site.author.googlescholar](https://scholar.google.com/citations?user=p1q3zRUAAAAJ&hl=en)}}">my Google Scholar profile</a>.</div>
{% endif %}
Mingxiang Li, A Liouville-type theorem in conformally invariant equations, Math. Ann.(2023). 
Mingxiang Li,  Xingwang Xu, Asymptotic behavior of conformal metrics on torus,  DCDS(2023). 
Mingxiang Li, A note on prescribed Q-curvature. Pacific J. Math. 319 (2022), no. 1, 181–188. 
Mingxiang Li, Xingwang Xu, A flow approach to mean field equation, Calc. Var. Partial Differential  Equations 61 (2022). 
 Xuezhang Chen , Mingxiang Li, Zirui Li, Xingwang Xu, On Gaussian curvature flow, J. Differential Equations 294 (2021). 
{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
