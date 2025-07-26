---
layout: publication
title: What Do Position Embeddings Learn? An Empirical Study Of Pre-trained Language
  Model Positional Encoding
authors: Yu-an Wang, Yun-nung Chen
conference: Proceedings of the 2020 Conference on Empirical Methods in Natural Language
  Processing (EMNLP)
year: 2020
bibkey: wang2020what
citations: 68
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2010.04903'}]
tags: ["EMNLP", "Training Techniques"]
short_authors: Yu-an Wang, Yun-nung Chen
---
In recent years, pre-trained Transformers have dominated the majority of NLP
benchmark tasks. Many variants of pre-trained Transformers have kept breaking
out, and most focus on designing different pre-training objectives or variants
of self-attention. Embedding the position information in the self-attention
mechanism is also an indispensable factor in Transformers however is often
discussed at will. Therefore, this paper carries out an empirical study on
position embeddings of mainstream pre-trained Transformers, which mainly
focuses on two questions: 1) Do position embeddings really learn the meaning of
positions? 2) How do these different learned position embeddings affect
Transformers for NLP tasks? This paper focuses on providing a new insight of
pre-trained position embeddings through feature-level analysis and empirical
experiments on most of iconic NLP tasks. It is believed that our experimental
results can guide the future work to choose the suitable positional encoding
function for specific tasks given the application property.