---
layout: publication
title: 'Vision As A Dialect: Unifying Visual Understanding And Generation Via Text-aligned
  Representations'
authors: Jiaming Han, Hao Chen, Yang Zhao, Hanyu Wang, Qi Zhao, Ziyan Yang, Hao He,
  Xiangyu Yue, Lu Jiang
conference: No Venue
year: 2025
bibkey: han2025vision
additional_links: [{name: Code, url: 'https://tar.csuhan.com'}, {name: Code, url: 'https://huggingface.co/discussions/paper/685a07520e4ad7e2197584cf'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2506.18898'}]
tags: ["Efficiency", "Tools", "Training Techniques"]
short_authors: Han et al.
---
This paper presents a multimodal framework that attempts to unify visual understanding and generation within a shared discrete semantic representation. At its core is the Text-Aligned Tokenizer (TA-Tok), which converts images into discrete tokens using a text-aligned codebook projected from a large language model's (LLM) vocabulary. By integrating vision and text into a unified space with an expanded vocabulary, our multimodal LLM, Tar, enables cross-modal input and output through a shared interface, without the need for modality-specific designs. Additionally, we propose scale-adaptive encoding and decoding to balance efficiency and visual detail, along with a generative de-tokenizer to produce high-fidelity visual outputs. To address diverse decoding needs, we utilize two complementary de-tokenizers: a fast autoregressive model and a diffusion-based model. To enhance modality fusion, we investigate advanced pre-training tasks, demonstrating improvements in both visual understanding and generation. Experiments across benchmarks show that Tar matches or surpasses existing multimodal LLM methods, achieving faster convergence and greater training efficiency. Code, models, and data are available at https://tar.csuhan.com

https://huggingface.co/discussions/paper/685a07520e4ad7e2197584cf