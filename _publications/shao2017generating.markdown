---
layout: publication
title: Generating High-quality And Informative Conversation Responses With Sequence-to-sequence
  Models
authors: Louis Shao, Stephan Gouws, Denny Britz, Anna Goldie, Brian Strope, Ray Kurzweil
conference: Proceedings of the 2017 Conference on Empirical Methods in Natural Language
  Processing
year: 2017
bibkey: shao2017generating
citations: 194
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1701.03185'}]
tags: ["EMNLP"]
short_authors: Shao et al.
---
Sequence-to-sequence models have been applied to the conversation response
generation problem where the source sequence is the conversation history and
the target sequence is the response. Unlike translation, conversation
responding is inherently creative. The generation of long, informative,
coherent, and diverse responses remains a hard task. In this work, we focus on
the single turn setting. We add self-attention to the decoder to maintain
coherence in longer responses, and we propose a practical approach, called the
glimpse-model, for scaling to large datasets. We introduce a stochastic
beam-search algorithm with segment-by-segment reranking which lets us inject
diversity earlier in the generation process. We trained on a combined data set
of over 2.3B conversation messages mined from the web. In human evaluation
studies, our method produces longer responses overall, with a higher proportion
rated as acceptable and excellent as length increases, compared to baseline
sequence-to-sequence models with explicit length-promotion. A back-off strategy
produces better responses overall, in the full spectrum of lengths.