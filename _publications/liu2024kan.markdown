---
layout: publication
title: 'KAN: Kolmogorov-arnold Networks'
authors: "Ziming Liu, Yixuan Wang, Sachin Vaidya, Fabian Ruehle, James Halverson,\
  \ Marin Solja\u010Di\u0107, Thomas Y. Hou, Max Tegmark"
conference: No Venue
year: 2024
bibkey: liu2024kan
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2404.19756'}]
tags: ["Efficiency"]
short_authors: Liu et al.
---
Inspired by the Kolmogorov-Arnold representation theorem, we propose Kolmogorov-Arnold Networks (KANs) as promising alternatives to Multi-Layer Perceptrons (MLPs). While MLPs have fixed activation functions on nodes ("neurons"), KANs have learnable activation functions on edges ("weights"). KANs have no linear weights at all -- every weight parameter is replaced by a univariate function parametrized as a spline. We show that this seemingly simple change makes KANs outperform MLPs in terms of accuracy and interpretability. For accuracy, much smaller KANs can achieve comparable or better accuracy than much larger MLPs in data fitting and PDE solving. Theoretically and empirically, KANs possess faster neural scaling laws than MLPs. For interpretability, KANs can be intuitively visualized and can easily interact with human users. Through two examples in mathematics and physics, KANs are shown to be useful collaborators helping scientists (re)discover mathematical and physical laws. In summary, KANs are promising alternatives for MLPs, opening opportunities for further improving today's deep learning models which rely heavily on MLPs.

https://huggingface.co/discussions/paper/6631c7768d7c840b14f53be5