---
layout: publication
title: 'Core^2: Collect, Reflect And Refine To Generate Better And Faster'
authors: Shitong Shao, Zikai Zhou, Dian Xie, Yuetong Fang, Tian Ye, Lichen Bai, Zeke
  Xie
conference: No Venue
year: 2025
bibkey: shao2025core
additional_links: [{name: Code, url: 'https://github.com/xie-lab-ml/CoRe/tree/main'},
  {name: Code, url: 'https://huggingface.co/discussions/paper/67d3dafb0034469b0d6ccac0'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2503.09662'}]
tags: ["Efficiency", "Has Code"]
short_authors: Shao et al.
---
Making text-to-image (T2I) generative model sample both fast and well represents a promising research direction. Previous studies have typically focused on either enhancing the visual quality of synthesized images at the expense of sampling efficiency or dramatically accelerating sampling without improving the base model's generative capacity. Moreover, nearly all inference methods have not been able to ensure stable performance simultaneously on both diffusion models (DMs) and visual autoregressive models (ARMs). In this paper, we introduce a novel plug-and-play inference paradigm, CoRe^2, which comprises three subprocesses: Collect, Reflect, and Refine. CoRe^2 first collects classifier-free guidance (CFG) trajectories, and then use collected data to train a weak model that reflects the easy-to-learn contents while reducing number of function evaluations during inference by half. Subsequently, CoRe^2 employs weak-to-strong guidance to refine the conditional output, thereby improving the model's capacity to generate high-frequency and realistic content, which is difficult for the base model to capture. To the best of our knowledge, CoRe^2 is the first to demonstrate both efficiency and effectiveness across a wide range of DMs, including SDXL, SD3.5, and FLUX, as well as ARMs like LlamaGen. It has exhibited significant performance improvements on HPD v2, Pick-of-Pic, Drawbench, GenEval, and T2I-Compbench. Furthermore, CoRe^2 can be seamlessly integrated with the state-of-the-art Z-Sampling, outperforming it by 0.3 and 0.16 on PickScore and AES, while achieving 5.64s time saving using SD3.5.Code is released at https://github.com/xie-lab-ml/CoRe/tree/main.

https://huggingface.co/discussions/paper/67d3dafb0034469b0d6ccac0