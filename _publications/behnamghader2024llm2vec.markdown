---
layout: publication
title: 'Llm2vec: Large Language Models Are Secretly Powerful Text Encoders'
authors: Parishad Behnamghader, Vaibhav Adlakha, Marius Mosbach, Dzmitry Bahdanau,
  Nicolas Chapados, Siva Reddy
conference: No Venue
year: 2024
bibkey: behnamghader2024llm2vec
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/6615e08f362219047e082fd4'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2404.05961'}]
tags: ["Evaluation", "Model Architecture"]
short_authors: Behnamghader et al.
---
Large decoder-only language models (LLMs) are the state-of-the-art models on most of today's NLP tasks and benchmarks. Yet, the community is only slowly adopting these models for text embedding tasks, which require rich contextualized representations. In this work, we introduce LLM2Vec, a simple unsupervised approach that can transform any decoder-only LLM into a strong text encoder. LLM2Vec consists of three simple steps: 1) enabling bidirectional attention, 2) masked next token prediction, and 3) unsupervised contrastive learning. We demonstrate the effectiveness of LLM2Vec by applying it to 3 popular LLMs ranging from 1.3B to 7B parameters and evaluate the transformed models on English word- and sequence-level tasks. We outperform encoder-only models by a large margin on word-level tasks and reach a new unsupervised state-of-the-art performance on the Massive Text Embeddings Benchmark (MTEB). Moreover, when combining LLM2Vec with supervised contrastive learning, we achieve state-of-the-art performance on MTEB among models that train only on publicly available data. Our strong empirical results and extensive analysis demonstrate that LLMs can be effectively transformed into universal text encoders in a parameter-efficient manner without the need for expensive adaptation or synthetic GPT-4 generated data.

https://huggingface.co/discussions/paper/6615e08f362219047e082fd4