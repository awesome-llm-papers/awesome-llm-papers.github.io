---
layout: publication
title: 'Retrollm: Empowering Large Language Models To Retrieve Fine-grained Evidence
  Within Generation'
authors: Xiaoxi Li, Jiajie Jin, Yujia Zhou, Yongkang Wu, Zhonghua Li, Qi Ye, Zhicheng
  Dou
conference: No Venue
year: 2024
bibkey: li2024retrollm
additional_links: [{name: Code, url: 'https://github.com/sunnynexus/RetroLLM'}, {
    name: Code, url: 'https://huggingface.co/discussions/paper/6760ec679e797e610c597a17'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2412.11919'}]
tags: ["Has Code", "RAG", "Tools"]
short_authors: Li et al.
---
Large language models (LLMs) exhibit remarkable generative capabilities but often suffer from hallucinations. Retrieval-augmented generation (RAG) offers an effective solution by incorporating external knowledge, but existing methods still face several limitations: additional deployment costs of separate retrievers, redundant input tokens from retrieved text chunks, and the lack of joint optimization of retrieval and generation. To address these issues, we propose RetroLLM, a unified framework that integrates retrieval and generation into a single, cohesive process, enabling LLMs to directly generate fine-grained evidence from the corpus with constrained decoding. Moreover, to mitigate false pruning in the process of constrained evidence generation, we introduce (1) hierarchical FM-Index constraints, which generate corpus-constrained clues to identify a subset of relevant documents before evidence generation, reducing irrelevant decoding space; and (2) a forward-looking constrained decoding strategy, which considers the relevance of future sequences to improve evidence accuracy. Extensive experiments on five open-domain QA datasets demonstrate RetroLLM's superior performance across both in-domain and out-of-domain tasks. The code is available at https://github.com/sunnynexus/RetroLLM.

https://huggingface.co/discussions/paper/6760ec679e797e610c597a17