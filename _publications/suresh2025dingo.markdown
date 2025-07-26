---
layout: publication
title: 'DINGO: Constrained Inference For Diffusion Llms'
authors: Tarun Suresh, Debangshu Banerjee, Shubham Ugare, Sasa Misailovic, Gagandeep
  Singh
conference: No Venue
year: 2025
bibkey: suresh2025dingo
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2505.23061'}]
tags: ["Efficiency"]
short_authors: Suresh et al.
---
Diffusion LLMs have emerged as a promising alternative to conventional autoregressive LLMs, offering significant potential for improved runtime efficiency. However, existing diffusion models lack the ability to provably enforce user-specified formal constraints, such as regular expressions, which makes them unreliable for tasks that require structured outputs, such as fixed-schema JSON generation. Unlike autoregressive models that generate tokens sequentially, diffusion LLMs predict a block of tokens in parallel. This parallelism makes traditional constrained decoding algorithms, which are designed for sequential token prediction, ineffective at preserving the true output distribution. To address this limitation, we propose DINGO, a dynamic programming-based constrained decoding strategy that is both efficient and provably distribution-preserving. DINGO enables sampling of output strings with the highest probability under the model's predicted distribution, while strictly satisfying any user-specified regular expression. On standard symbolic math and JSON generation benchmarks, DINGO achieves up to a 68 percentage point improvement over unconstrained inference

https://huggingface.co/discussions/paper/683fc4038de3ffc5838c3fd8