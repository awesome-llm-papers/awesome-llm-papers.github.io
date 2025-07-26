---
layout: publication
title: 'Singlora: Low Rank Adaptation Using A Single Matrix'
authors: "David Bensa\xEFd, Noam Rotstein, Roy Velich, Daniel Bensa\xEFd, Ron Kimmel"
conference: No Venue
year: 2025
bibkey: "bensa\xEFd2025singlora"
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2507.05566'}]
tags: ["Efficiency", "Fine-Tuning", "Training Techniques"]
short_authors: "Bensa\xEFd et al."
---
Low-Rank Adaptation (LoRA) has significantly advanced parameter-efficient fine-tuning of large pretrained models. LoRA augments the pre-trained weights of a model by adding the product of two smaller matrices that together form a low-rank matrix update. Recent research has shown that scale disparities between these two matrices often cause unstable training dynamics, leading to suboptimal performance. In this paper, we propose SingLoRA, which reformulates low-rank adaptation by learning the weights update as a decomposition of a single low-rank matrix multiplied by its transpose. This simple design inherently removes inter-matrix scale conflicts, ensuring stable optimization, and roughly halves the parameter count. We analyze SingLoRA within the infinite-width neural network framework, showing that it guarantees stable feature learning by construction. Extensive experiments on multiple tasks validate these benefits. In common sense reasoning, fine-tuning LLama 7B on MNLI with SingLoRA achieves 91.3% accuracy - surpassing LoRA (89.1%) and LoRA+ (90.2%) - while using only 60% of their parameter budget. In image generation, fine-tuning Stable Diffusion with SingLoRA significantly improves image fidelity on DreamBooth, achieving a DINO similarity score of 0.151, compared to scores of 0.148 and 0.143 for DoRA and LoRA, respectively.

https://huggingface.co/discussions/paper/686e0a5dcb5725779c60b4eb