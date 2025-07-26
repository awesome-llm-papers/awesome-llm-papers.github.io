---
layout: publication
title: 'Ferret-v2: An Improved Baseline For Referring And Grounding With Large Language
  Models'
authors: Haotian Zhang, Haoxuan You, Philipp Dufter, Bowen Zhang, Chen Chen, Hong-you
  Chen, Tsu-jui Fu, William Yang Wang, Shih-fu Chang, Zhe Gan, Yinfei Yang
conference: No Venue
year: 2024
bibkey: zhang2024ferret
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/661891f4cbf0f99bc8116e20'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2404.07973'}]
tags: ["Training Techniques"]
short_authors: Zhang et al.
---
While Ferret seamlessly integrates regional understanding into the Large Language Model (LLM) to facilitate its referring and grounding capability, it poses certain limitations: constrained by the pre-trained fixed visual encoder and failed to perform well on broader tasks. In this work, we unveil Ferret-v2, a significant upgrade to Ferret, with three key designs. (1) Any resolution grounding and referring: A flexible approach that effortlessly handles higher image resolution, improving the model's ability to process and understand images in greater detail. (2) Multi-granularity visual encoding: By integrating the additional DINOv2 encoder, the model learns better and diverse underlying contexts for global and fine-grained visual information. (3) A three-stage training paradigm: Besides image-caption alignment, an additional stage is proposed for high-resolution dense alignment before the final instruction tuning. Experiments show that Ferret-v2 provides substantial improvements over Ferret and other state-of-the-art methods, thanks to its high-resolution scaling and fine-grained visual processing.

https://huggingface.co/discussions/paper/661891f4cbf0f99bc8116e20