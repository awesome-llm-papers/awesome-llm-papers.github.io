---
layout: publication
title: A Silver Bullet Or A Compromise For Full Attention? A Comprehensive Study Of
  Gist Token-based Context Compression
authors: Chenlong Deng, Zhisong Zhang, Kelong Mao, Shuaiyi Li, Xinting Huang, Dong
  Yu, Zhicheng Dou
conference: No Venue
year: 2024
bibkey: deng2024silver
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2412.17483'}]
tags: ["Efficiency"]
short_authors: Deng et al.
---
In this work, we provide a thorough investigation of gist-based context compression methods to improve long-context processing in large language models. We focus on two key questions: (1) How well can these methods replace full attention models? and (2) What potential failure patterns arise due to compression? Through extensive experiments, we show that while gist-based compression can achieve near-lossless performance on tasks like retrieval-augmented generation and long-document QA, it faces challenges in tasks like synthetic recall. Furthermore, we identify three key failure patterns: lost by the boundary, lost if surprise, and lost along the way. To mitigate these issues, we propose two effective strategies: fine-grained autoencoding, which enhances the reconstruction of original token information, and segment-wise token importance estimation, which adjusts optimization based on token dependencies. Our work provides valuable insights into the understanding of gist token-based context compression and offers practical strategies for improving compression capabilities.

https://huggingface.co/discussions/paper/676a2a3fbce62ec5a02c4ace