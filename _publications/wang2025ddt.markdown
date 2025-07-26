---
layout: publication
title: 'DDT: Decoupled Diffusion Transformer'
authors: Shuai Wang, Zhi Tian, Weilin Huang, Limin Wang
conference: No Venue
year: 2025
bibkey: wang2025ddt
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/67f726dd0b5aa5777fd3a463'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2504.05741'}]
tags: ["Model Architecture"]
short_authors: Wang et al.
---
Diffusion transformers have demonstrated remarkable generation quality, albeit requiring longer training iterations and numerous inference steps. In each denoising step, diffusion transformers encode the noisy inputs to extract the lower-frequency semantic component and then decode the higher frequency with identical modules. This scheme creates an inherent optimization dilemma: encoding low-frequency semantics necessitates reducing high-frequency components, creating tension between semantic encoding and high-frequency decoding. To resolve this challenge, we propose a new \color\{ddtD\}ecoupled \color\{ddtD\}iffusion \color\{ddtT\}ransformer~(\color\{ddtDDT\}), with a decoupled design of a dedicated condition encoder for semantic extraction alongside a specialized velocity decoder. Our experiments reveal that a more substantial encoder yields performance improvements as model size increases. For ImageNet 256times256, Our DDT-XL/2 achieves a new state-of-the-art performance of \{1.31 FID\}~(nearly 4times faster training convergence compared to previous diffusion transformers). For ImageNet 512times512, Our DDT-XL/2 achieves a new state-of-the-art FID of 1.28. Additionally, as a beneficial by-product, our decoupled architecture enhances inference speed by enabling the sharing self-condition between adjacent denoising steps. To minimize performance degradation, we propose a novel statistical dynamic programming approach to identify optimal sharing strategies.

https://huggingface.co/discussions/paper/67f726dd0b5aa5777fd3a463