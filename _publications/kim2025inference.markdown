---
layout: publication
title: Inference-time Scaling For Flow Models Via Stochastic Generation And Rollover
  Budget Forcing
authors: Jaihoon Kim, Taehoon Yoon, Jisung Hwang, Minhyuk Sung
conference: No Venue
year: 2025
bibkey: kim2025inference
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2503.19385'}]
tags: ["Efficiency"]
short_authors: Kim et al.
---
We propose an inference-time scaling approach for pretrained flow models. Recently, inference-time scaling has gained significant attention in LLMs and diffusion models, improving sample quality or better aligning outputs with user preferences by leveraging additional computation. For diffusion models, particle sampling has allowed more efficient scaling due to the stochasticity at intermediate denoising steps. On the contrary, while flow models have gained popularity as an alternative to diffusion models--offering faster generation and high-quality outputs in state-of-the-art image and video generative models--efficient inference-time scaling methods used for diffusion models cannot be directly applied due to their deterministic generative process. To enable efficient inference-time scaling for flow models, we propose three key ideas: 1) SDE-based generation, enabling particle sampling in flow models, 2) Interpolant conversion, broadening the search space and enhancing sample diversity, and 3) Rollover Budget Forcing (RBF), an adaptive allocation of computational resources across timesteps to maximize budget utilization. Our experiments show that SDE-based generation, particularly variance-preserving (VP) interpolant-based generation, improves the performance of particle sampling methods for inference-time scaling in flow models. Additionally, we demonstrate that RBF with VP-SDE achieves the best performance, outperforming all previous inference-time scaling approaches.

https://huggingface.co/discussions/paper/67e36245d8da46951f85802c