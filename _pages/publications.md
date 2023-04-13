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
\* indicates Equal Contribution.
## Preprints
- Deformable Kernel Expansion Model for Efficient Arbitrary-shaped Scene Text Detection. Tao He, Sheng Huang, **Wenhao Tang**, and Bo Liu. [arxiv](https://arxiv.org/abs/2303.15737)
- R$^2$T-MIL: Re-embedded Regional Transformer based Multiple Instance Learning for Whole Slide Image Classification. **Wenhao Tang**, Sheng Huang, Xiaoxian Zhang, Fengtao Zhou, Yi Zhang, and Bo Liu. [ICCV Under review]().
- Multiple Instance Learning Framework with Masked Hard Instance Mining for Whole Slide Image Classification. **Wenhao Tang**, Sheng Huang, Xiaoxian Zhang, Fengtao Zhou, Yi Zhang, and Bo Liu. [ICCV Under review]().

## Reports
- Towards Glimpsing Optimizer in Deep Learning: from SGD to Lookahead to the Future. **Wenhao Tang**. <a href="{{ base_path }}/files/towards_glimpsing_optimizer_in_deep_learning__from_sgd_to_lookahead_to_the_future.pdf">pdf</a>

## Papers
{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
