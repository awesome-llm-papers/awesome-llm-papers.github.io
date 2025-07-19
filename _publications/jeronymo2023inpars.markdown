---
layout: publication
title: 'Inpars-v2: Large Language Models As Efficient Dataset Generators For Information
  Retrieval'
authors: Jeronymo et al.
conference: Proceedings of the 45th International ACM SIGIR Conference on Research
  and Development in Information Retrieval
year: 2023
bibkey: jeronymo2023inpars
citations: 60
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2301.01820'}]
tags: [Training Techniques, GPT, Prompting, Evaluation, Model Architecture, Few Shot,
  SIGIR, Datasets]
---
Recently, InPars introduced a method to efficiently use large language models
(LLMs) in information retrieval tasks: via few-shot examples, an LLM is induced
to generate relevant queries for documents. These synthetic query-document
pairs can then be used to train a retriever. However, InPars and, more
recently, Promptagator, rely on proprietary LLMs such as GPT-3 and FLAN to
generate such datasets. In this work we introduce InPars-v2, a dataset
generator that uses open-source LLMs and existing powerful rerankers to select
synthetic query-document pairs for training. A simple BM25 retrieval pipeline
followed by a monoT5 reranker finetuned on InPars-v2 data achieves new
state-of-the-art results on the BEIR benchmark. To allow researchers to further
improve our method, we open source the code, synthetic data, and finetuned
models: https://github.com/zetaalphavector/inPars/tree/master/tpu