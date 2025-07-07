---
layout: publication
title: 'Lamini-lm: A Diverse Herd Of Distilled Models From Large-scale Instructions'
authors: Minghao Wu, Abdul Waheed, Chiyu Zhang, Muhammad Abdul-mageed, Alham Fikri
  Aji
conference: Arxiv
year: 2023
citations: 19
bibkey: wu2023lamini
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2304.14402'}]
tags: [Training Techniques, GPT, RAG, Fine-Tuning, Model Architecture]
---
Large language models (LLMs) with instruction fine-tuning demonstrate
superior generative capabilities. However, these models are resource-intensive.
To alleviate this issue, we explore distilling knowledge from instruction-tuned
LLMs into much smaller ones. To this end, we carefully develop a large set of
2.58M instructions based on both existing and newly-generated instructions. In
addition to being sizable, we design our instructions to cover a broad set of
topics to ensure diversity. Extensive analysis of our instruction dataset
confirms its diversity, and we generate responses for these instructions using
gpt-3.5-turbo. Leveraging these instructions, we fine-tune a diverse herd of
models, collectively referred to as LaMini-LM, which includes models from both
the encoder-decoder and decoder-only families, with varying sizes. We evaluate
the performance of our models using automatic metrics on 15 different natural
language processing (NLP) benchmarks, as well as through human assessment. The
results demonstrate that our proposed LaMini-LM models are comparable to
competitive baselines, while being much smaller in size.