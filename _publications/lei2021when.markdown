---
layout: publication
title: 'When Attention Meets Fast Recurrence: Training Language Models With Reduced
  Compute'
authors: Tao Lei
conference: Proceedings of the 2021 Conference on Empirical Methods in Natural Language
  Processing
year: 2021
citations: 16
bibkey: lei2021when
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2102.12459'}]
tags: [Language Modeling, Model Architecture, Attention Mechanism, Transformer, RAG,
  Efficiency and Optimization, Training Techniques, Time Series]
---
Large language models have become increasingly difficult to train because of
the growing computation time and cost. In this work, we present SRU++, a
highly-efficient architecture that combines fast recurrence and attention for
sequence modeling. SRU++ exhibits strong modeling capacity and training
efficiency. On standard language modeling tasks such as Enwik8, Wiki-103 and
Billion Word datasets, our model obtains better bits-per-character and
perplexity while using 3x-10x less training cost compared to top-performing
Transformer models. For instance, our model achieves a state-of-the-art result
on the Enwik8 dataset using 1.6 days of training on an 8-GPU machine. We
further demonstrate that SRU++ requires minimal attention for near
state-of-the-art performance. Our results suggest jointly leveraging fast
recurrence with little attention as a promising direction for accelerating
model training and inference.