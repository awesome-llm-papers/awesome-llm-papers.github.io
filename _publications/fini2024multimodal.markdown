---
layout: publication
title: Multimodal Autoregressive Pre-training Of Large Vision Encoders
authors: "Enrico Fini, Mustafa Shukor, Xiujun Li, Philipp Dufter, Michal Klein, David\
  \ Haldimann, Sai Aitharaju, Victor Guilherme Turrisi da Costa, Louis B\xE9thune,\
  \ Zhe Gan, Alexander T Toshev, Marcin Eichner, Moin Nabi, Yinfei Yang, Joshua M.\
  \ Susskind, Alaaeldin El-nouby"
conference: No Venue
year: 2024
bibkey: fini2024multimodal
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/67400d6580c7c8e332a60c50'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2411.14402'}]
tags: ["Training Techniques"]
short_authors: Fini et al.
---
We introduce a novel method for pre-training of large-scale vision encoders. Building on recent advancements in autoregressive pre-training of vision models, we extend this framework to a multimodal setting, i.e., images and text. In this paper, we present AIMV2, a family of generalist vision encoders characterized by a straightforward pre-training process, scalability, and remarkable performance across a range of downstream tasks. This is achieved by pairing the vision encoder with a multimodal decoder that autoregressively generates raw image patches and text tokens. Our encoders excel not only in multimodal evaluations but also in vision benchmarks such as localization, grounding, and classification. Notably, our AIMV2-3B encoder achieves 89.5% accuracy on ImageNet-1k with a frozen trunk. Furthermore, AIMV2 consistently outperforms state-of-the-art contrastive models (e.g., CLIP, SigLIP) in multimodal image understanding across diverse settings.

https://huggingface.co/discussions/paper/67400d6580c7c8e332a60c50