---
layout: publication
title: Multi-lora Composition For Image Generation
authors: Ming Zhong, Yelong Shen, Shuohang Wang, Yadong Lu, Yizhu Jiao, Siru Ouyang,
  Donghan Yu, Jiawei Han, Weizhu Chen
conference: No Venue
year: 2024
bibkey: zhong2024multi
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2402.16843'}]
tags: ["Model Architecture", "Tools"]
short_authors: Zhong et al.
---
Low-Rank Adaptation (LoRA) is extensively utilized in text-to-image models for the accurate rendition of specific elements like distinct characters or unique styles in generated images. Nonetheless, existing methods face challenges in effectively composing multiple LoRAs, especially as the number of LoRAs to be integrated grows, thus hindering the creation of complex imagery. In this paper, we study multi-LoRA composition through a decoding-centric perspective. We present two training-free methods: LoRA Switch, which alternates between different LoRAs at each denoising step, and LoRA Composite, which simultaneously incorporates all LoRAs to guide more cohesive image synthesis. To evaluate the proposed approaches, we establish ComposLoRA, a new comprehensive testbed as part of this research. It features a diverse range of LoRA categories with 480 composition sets. Utilizing an evaluation framework based on GPT-4V, our findings demonstrate a clear improvement in performance with our methods over the prevalent baseline, particularly evident when increasing the number of LoRAs in a composition.

https://huggingface.co/discussions/paper/65dd64e8ce348fc5b121505a