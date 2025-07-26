---
layout: publication
title: 'Jina-embeddings-v3: Multilingual Embeddings With Task Lora'
authors: "Saba Sturua, Isabelle Mohr, Mohammad Kalim Akram, Michael G\xFCnther, Bo\
  \ Wang, Markus Krimmel, Feng Wang, Georgios Mastrapas, Andreas Koukounas, Andreas\
  \ Koukounas, Nan Wang, Han Xiao"
conference: No Venue
year: 2024
bibkey: sturua2024jina
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2409.10173'}]
tags: ["Evaluation", "Fine-Tuning", "Memory & Context", "Training Techniques"]
short_authors: Sturua et al.
---
We introduce jina-embeddings-v3, a novel text embedding model with 570 million parameters, achieves state-of-the-art performance on multilingual data and long-context retrieval tasks, supporting context lengths of up to 8192 tokens. The model includes a set of task-specific Low-Rank Adaptation (LoRA) adapters to generate high-quality embeddings for query-document retrieval, clustering, classification, and text matching. Additionally, Matryoshka Representation Learning is integrated into the training process, allowing flexible truncation of embedding dimensions without compromising performance. Evaluation on the MTEB benchmark shows that jina-embeddings-v3 outperforms the latest proprietary embeddings from OpenAI and Cohere on English tasks, while achieving superior performance compared to multilingual-e5-large-instruct across all multilingual tasks.

https://huggingface.co/discussions/paper/66e926cbff154e75c55e59a7