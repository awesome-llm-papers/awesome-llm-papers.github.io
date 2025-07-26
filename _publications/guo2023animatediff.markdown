---
layout: publication
title: 'Animatediff: Animate Your Personalized Text-to-image Diffusion Models Without
  Specific Tuning'
authors: Yuwei Guo, Ceyuan Yang, Anyi Rao, Yaohui Wang, Yu Qiao, Dahua Lin, Bo Dai
conference: No Venue
year: 2023
bibkey: guo2023animatediff
additional_links: [{name: Code, url: 'https://animatediff.github.io/'}, {name: Code,
    url: 'https://huggingface.co/discussions/paper/64accd7db2f83dec96103647'}, {name: Paper,
    url: 'https://arxiv.org/abs/hf2307.04725'}]
tags: ["Has Code", "Tools"]
short_authors: Guo et al.
---
With the advance of text-to-image models (e.g., Stable Diffusion) and corresponding personalization techniques such as DreamBooth and LoRA, everyone can manifest their imagination into high-quality images at an affordable cost. Subsequently, there is a great demand for image animation techniques to further combine generated static images with motion dynamics. In this report, we propose a practical framework to animate most of the existing personalized text-to-image models once and for all, saving efforts in model-specific tuning. At the core of the proposed framework is to insert a newly initialized motion modeling module into the frozen text-to-image model and train it on video clips to distill reasonable motion priors. Once trained, by simply injecting this motion modeling module, all personalized versions derived from the same base T2I readily become text-driven models that produce diverse and personalized animated images. We conduct our evaluation on several public representative personalized text-to-image models across anime pictures and realistic photographs, and demonstrate that our proposed framework helps these models generate temporally smooth animation clips while preserving the domain and diversity of their outputs. Code and pre-trained weights will be publicly available at https://animatediff.github.io/ .

https://huggingface.co/discussions/paper/64accd7db2f83dec96103647