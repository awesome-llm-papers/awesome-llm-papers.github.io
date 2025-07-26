---
layout: publication
title: Attention-informed Mixed-language Training For Zero-shot Cross-lingual Task-oriented
  Dialogue Systems
authors: Zihan Liu, Genta Indra Winata, Zhaojiang Lin, Peng Xu, Pascale Fung
conference: Proceedings of the AAAI Conference on Artificial Intelligence
year: 2020
bibkey: liu2019attention
citations: 93
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1911.09273'}]
tags: ["AAAI", "Model Architecture", "Training Techniques"]
short_authors: Liu et al.
---
Recently, data-driven task-oriented dialogue systems have achieved promising
performance in English. However, developing dialogue systems that support
low-resource languages remains a long-standing challenge due to the absence of
high-quality data. In order to circumvent the expensive and time-consuming data
collection, we introduce Attention-Informed Mixed-Language Training (MLT), a
novel zero-shot adaptation method for cross-lingual task-oriented dialogue
systems. It leverages very few task-related parallel word pairs to generate
code-switching sentences for learning the inter-lingual semantics across
languages. Instead of manually selecting the word pairs, we propose to extract
source words based on the scores computed by the attention layer of a trained
English task-related model and then generate word pairs using existing
bilingual dictionaries. Furthermore, intensive experiments with different
cross-lingual embeddings demonstrate the effectiveness of our approach.
Finally, with very few word pairs, our model achieves significant zero-shot
adaptation performance improvements in both cross-lingual dialogue state
tracking and natural language understanding (i.e., intent detection and slot
filling) tasks compared to the current state-of-the-art approaches, which
utilize a much larger amount of bilingual data.