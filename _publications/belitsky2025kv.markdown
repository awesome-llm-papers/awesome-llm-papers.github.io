---
layout: publication
title: KV Cache Steering For Inducing Reasoning In Small Language Models
authors: Max Belitsky, Dawid J. Kopiczko, Michael Dorkenwald, M. Jehanzeb Mirza, Cees
  G. M. Snoek, Yuki M. Asano
conference: No Venue
year: 2025
bibkey: belitsky2025kv
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2507.08799'}]
tags: ["Efficiency", "Memory & Context", "Model Architecture"]
short_authors: Belitsky et al.
---
We propose cache steering, a lightweight method for implicit steering of language models via a one-shot intervention applied directly to the key-value cache. To validate its effectiveness, we apply cache steering to induce chain-of-thought reasoning in small language models. Our approach leverages GPT-4o-generated reasoning traces to construct steering vectors that shift model behavior toward more explicit, multi-step reasoning without fine-tuning or prompt modifications. Experimental evaluations on diverse reasoning benchmarks demonstrate that cache steering improves both the qualitative structure of model reasoning and quantitative task performance. Compared to prior activation steering techniques that require continuous interventions, our one-shot cache steering offers substantial advantages in terms of hyperparameter stability, inference-time efficiency, and ease of integration, making it a more robust and practical solution for controlled generation.

https://huggingface.co/discussions/paper/6874ac1e257d4f043537038f