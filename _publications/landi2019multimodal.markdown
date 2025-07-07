---
layout: publication
title: Multimodal Attention Networks For Low-level Vision-and-language Navigation
authors: Federico Landi, Lorenzo Baraldi, Marcella Cornia, Massimiliano Corsini, Rita
  Cucchiara
conference: Arxiv
year: 2019
citations: 22
bibkey: landi2019multimodal
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1911.12377'}, {name: Code,
    url: 'https://github.com/aimagelab/perceive-transform-and-act'}]
tags: [Transformer, Merging, Attention Mechanism, Agentic, Reinforcement Learning,
  Has Code, Multimodal Models, Model Architecture]
---
Vision-and-Language Navigation (VLN) is a challenging task in which an agent
needs to follow a language-specified path to reach a target destination. The
goal gets even harder as the actions available to the agent get simpler and
move towards low-level, atomic interactions with the environment. This setting
takes the name of low-level VLN. In this paper, we strive for the creation of
an agent able to tackle three key issues: multi-modality, long-term
dependencies, and adaptability towards different locomotive settings. To that
end, we devise "Perceive, Transform, and Act" (PTA): a fully-attentive VLN
architecture that leaves the recurrent approach behind and the first
Transformer-like architecture incorporating three different modalities -
natural language, images, and low-level actions for the agent control. In
particular, we adopt an early fusion strategy to merge lingual and visual
information efficiently in our encoder. We then propose to refine the decoding
phase with a late fusion extension between the agent's history of actions and
the perceptual modalities. We experimentally validate our model on two
datasets: PTA achieves promising results in low-level VLN on R2R and achieves
good performance in the recently proposed R4R benchmark. Our code is publicly
available at https://github.com/aimagelab/perceive-transform-and-act.