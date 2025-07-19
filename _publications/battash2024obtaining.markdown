---
layout: publication
title: Obtaining Favorable Layouts For Multiple Object Generation
authors: Battash et al.
conference: Proceedings of the AAAI Conference on Artificial Intelligence
year: 2024
bibkey: battash2024obtaining
citations: 57
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2405.00791'}]
tags: [Attention Mechanism, Alt, Prompting, Model Architecture, Reinforcement Learning,
  AAAI, Merging]
---
Large-scale text-to-image models that can generate high-quality and diverse
images based on textual prompts have shown remarkable success. These models aim
ultimately to create complex scenes, and addressing the challenge of
multi-subject generation is a critical step towards this goal. However, the
existing state-of-the-art diffusion models face difficulty when generating
images that involve multiple subjects. When presented with a prompt containing
more than one subject, these models may omit some subjects or merge them
together. To address this challenge, we propose a novel approach based on a
guiding principle. We allow the diffusion model to initially propose a layout,
and then we rearrange the layout grid. This is achieved by enforcing
cross-attention maps (XAMs) to adhere to proposed masks and by migrating pixels
from latent maps to new locations determined by us. We introduce new loss terms
aimed at reducing XAM entropy for clearer spatial definition of subjects,
reduce the overlap between XAMs, and ensure that XAMs align with their
respective masks. We contrast our approach with several alternative methods and
show that it more faithfully captures the desired concepts across a variety of
text prompts.