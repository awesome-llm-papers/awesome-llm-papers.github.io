---
layout: publication
title: 'Codebpe: Investigating Subtokenization Options For Large Language Model Pretraining
  On Source Code'
authors: Chirkova Nadezhda, Troshin Sergey
conference: Proceedings of the 37th IEEE/ACM International Conference on Automated
  Software Engineering
year: 2023
bibkey: chirkova2023codebpe
citations: 53
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2308.00683'}]
tags: [Model Architecture, Training Techniques, Tokenization, LLM For Code, LLM for
    Code, Transformer, RAG]
---
Recent works have widely adopted large language model pretraining for source
code, suggested source code-specific pretraining objectives and investigated
the applicability of various Transformer-based language model architectures for
source code. This work investigates another important aspect of such models,
namely the effect of different subtokenization options, and aims at identifying
most effective and length-efficient subtokenizations, taking into account code
specifics. We propose subtokenziation that reduces average length by 17%
without downstream performance drop, and show that a carefully chosen
subtokenization may improve quality by 0.5-2%, possibly with some length
increase.