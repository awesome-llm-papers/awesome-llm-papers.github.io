---
layout: publication
title: Repurposing Decoder-transformer Language Models For Abstractive Summarization
authors: "de Oliveira Luke, Rodrigo Alfredo L\xE1inez"
conference: Proceedings of the 2020 Conference on Empirical Methods in Natural Language
  Processing (EMNLP)
year: 2019
bibkey: deoliveira2019repurposing
citations: 75
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1909.00325'}]
tags: [RAG, EMNLP, Ethics And Bias, Transformer, Model Architecture, Efficiency And
    Optimization, Language Modeling, Fine Tuning]
---
Neural network models have shown excellent fluency and performance when
applied to abstractive summarization. Many approaches to neural abstractive
summarization involve the introduction of significant inductive bias,
exemplified through the use of components such as pointer-generator
architectures, coverage, and partially extractive procedures, designed to mimic
the process by which humans summarize documents. We show that it is possible to
attain competitive performance by instead directly viewing summarization as a
language modeling problem and effectively leveraging transfer learning. We
introduce a simple procedure built upon decoder-transformers to obtain highly
competitive ROUGE scores for summarization performance using a language
modeling loss alone, with no beam-search or other decoding-time optimization,
and instead relying on efficient nucleus sampling and greedy decoding.