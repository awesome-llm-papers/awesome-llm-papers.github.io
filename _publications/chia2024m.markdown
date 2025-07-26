---
layout: publication
title: 'M-longdoc: A Benchmark For Multimodal Super-long Document Understanding And
  A Retrieval-aware Tuning Framework'
authors: Yew Ken Chia, Liying Cheng, Hou Pong Chan, Chaoqun Liu, Maojia Song, Sharifah
  Mahani Aljunied, Soujanya Poria, Lidong Bing
conference: No Venue
year: 2024
bibkey: chia2024m
additional_links: [{name: Code, url: 'https://multimodal-documents.github.io'}, {
    name: Code, url: 'https://huggingface.co/discussions/paper/6732c7927c79bb4d06689191'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2411.06176'}]
tags: ["Evaluation"]
short_authors: Chia et al.
---
The ability to understand and answer questions over documents can be useful in many business and practical applications. However, documents often contain lengthy and diverse multimodal contents such as texts, figures, and tables, which are very time-consuming for humans to read thoroughly. Hence, there is an urgent need to develop effective and automated methods to aid humans in this task. In this work, we introduce M-LongDoc, a benchmark of 851 samples, and an automated framework to evaluate the performance of large multimodal models. We further propose a retrieval-aware tuning approach for efficient and effective multimodal document reading. Compared to existing works, our benchmark consists of more recent and lengthy documents with hundreds of pages, while also requiring open-ended solutions and not just extractive answers. To our knowledge, our training framework is the first to directly address the retrieval setting for multimodal long documents. To enable tuning open-source models, we construct a training corpus in a fully automatic manner for the question-answering task over such documents. Experiments show that our tuning approach achieves a relative improvement of 4.6% for the correctness of model responses, compared to the baseline open-source models. Our data, code, and models are available at https://multimodal-documents.github.io.

https://huggingface.co/discussions/paper/6732c7927c79bb4d06689191