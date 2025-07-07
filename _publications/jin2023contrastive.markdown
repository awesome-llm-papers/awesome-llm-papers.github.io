---
layout: publication
title: 'Medcpt: Contrastive Pre-trained Transformers With Large-scale Pubmed Search
  Logs For Zero-shot Biomedical Information Retrieval'
authors: Qiao Jin et al.
conference: Arxiv
year: 2023
citations: 35
bibkey: jin2023contrastive
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2307.00589'}]
tags: [GPT, Transformer, Training Techniques, Reinforcement Learning, Model Architecture]
---
Information retrieval (IR) is essential in biomedical knowledge acquisition
and clinical decision support. While recent progress has shown that language
model encoders perform better semantic retrieval, training such models requires
abundant query-article annotations that are difficult to obtain in biomedicine.
As a result, most biomedical IR systems only conduct lexical matching. In
response, we introduce MedCPT, a first-of-its-kind Contrastively Pre-trained
Transformer model for zero-shot semantic IR in biomedicine. To train MedCPT, we
collected an unprecedented scale of 255 million user click logs from PubMed.
With such data, we use contrastive learning to train a pair of
closely-integrated retriever and re-ranker. Experimental results show that
MedCPT sets new state-of-the-art performance on six biomedical IR tasks,
outperforming various baselines including much larger models such as
GPT-3-sized cpt-text-XL. In addition, MedCPT also generates better biomedical
article and sentence representations for semantic evaluations. As such, MedCPT
can be readily applied to various real-world biomedical IR tasks.