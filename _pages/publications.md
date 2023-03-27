---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.
{% endif %}


{% include base_path %}

## Preprints
- Deformable Kernel Expansion Model for Efficient Arbitrary-shaped Scene Text Detection. Tao He, Sheng Huang, **Wenhao Tang**, and Bo Liu. [arxiv](https://arxiv.org/pdf/2203.16782)
- R$^2$T-MIL: Re-embedded Regional Transformer based Multiple Instance Learning for Whole Slide Image Classification. **Wenhao Tang**, Sheng Huang, Xiaoxian Zhang, Fengtao Zhou, Yi Zhang, and Bo Liu. [Under review]()
- Multiple Instance Learning Framework with Masked Hard Instance Mining for Whole Slide Image Classification. **Wenhao Tang**, Sheng Huang, Xiaoxian Zhang, Fengtao Zhou, Yi Zhang, and Bo Liu. [Under review]()

## Papers
{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
