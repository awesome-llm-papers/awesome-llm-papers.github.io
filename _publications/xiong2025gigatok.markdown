---
layout: publication
title: 'Gigatok: Scaling Visual Tokenizers To 3 Billion Parameters For Autoregressive
  Image Generation'
authors: Tianwei Xiong, Jun Hao Liew, Zilong Huang, Jiashi Feng, Xihui Liu
conference: No Venue
year: 2025
bibkey: xiong2025gigatok
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/67fc8e38864dfcbd93d3b836'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2504.08736'}]
tags: ["Training Techniques"]
short_authors: Xiong et al.
---
In autoregressive (AR) image generation, visual tokenizers compress images into compact discrete latent tokens, enabling efficient training of downstream autoregressive models for visual generation via next-token prediction. While scaling visual tokenizers improves image reconstruction quality, it often degrades downstream generation quality -- a challenge not adequately addressed in existing literature. To address this, we introduce GigaTok, the first approach to simultaneously improve image reconstruction, generation, and representation learning when scaling visual tokenizers. We identify the growing complexity of latent space as the key factor behind the reconstruction vs. generation dilemma. To mitigate this, we propose semantic regularization, which aligns tokenizer features with semantically consistent features from a pre-trained visual encoder. This constraint prevents excessive latent space complexity during scaling, yielding consistent improvements in both reconstruction and downstream autoregressive generation. Building on semantic regularization, we explore three key practices for scaling tokenizers:(1) using 1D tokenizers for better scalability, (2) prioritizing decoder scaling when expanding both encoder and decoder, and (3) employing entropy loss to stabilize training for billion-scale tokenizers. By scaling to 3 space billion parameters, GigaTok achieves state-of-the-art performance in reconstruction, downstream AR generation, and downstream AR representation quality.

https://huggingface.co/discussions/paper/67fc8e38864dfcbd93d3b836