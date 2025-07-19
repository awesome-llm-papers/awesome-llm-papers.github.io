---
layout: publication
title: Improving Question Generation With Sentence-level Semantic Matching And Answer
  Position Inferring
authors: Ma et al.
conference: Proceedings of the AAAI Conference on Artificial Intelligence
year: 2019
bibkey: ma2019improving
citations: 50
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1912.00879'}]
tags: [RAG, AAAI, Datasets, Merging]
---
Taking an answer and its context as input, sequence-to-sequence models have
made considerable progress on question generation. However, we observe that
these approaches often generate wrong question words or keywords and copy
answer-irrelevant words from the input. We believe that lacking global question
semantics and exploiting answer position-awareness not well are the key root
causes. In this paper, we propose a neural question generation model with two
concrete modules: sentence-level semantic matching and answer position
inferring. Further, we enhance the initial state of the decoder by leveraging
the answer-aware gated fusion mechanism. Experimental results demonstrate that
our model outperforms the state-of-the-art (SOTA) models on SQuAD and MARCO
datasets. Owing to its generality, our work also improves the existing models
significantly.