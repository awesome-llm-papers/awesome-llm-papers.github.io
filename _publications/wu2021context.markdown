---
layout: publication
title: A Context-aware Hierarchical BERT Fusion Network For Multi-turn Dialog Act
  Detection
authors: Ting-wei Wu, Ruolin Su, Biing-hwang Juang
conference: Proceedings of the AAAI Conference on Artificial Intelligence
year: 2021
bibkey: wu2021context
citations: 76
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2109.01267'}]
tags: ["AAAI", "Model Architecture"]
short_authors: Ting-wei Wu, Ruolin Su, Biing-hwang Juang
---
The success of interactive dialog systems is usually associated with the
quality of the spoken language understanding (SLU) task, which mainly
identifies the corresponding dialog acts and slot values in each turn. By
treating utterances in isolation, most SLU systems often overlook the semantic
context in which a dialog act is expected. The act dependency between turns is
non-trivial and yet critical to the identification of the correct semantic
representations. Previous works with limited context awareness have exposed the
inadequacy of dealing with complexity in multiproned user intents, which are
subject to spontaneous change during turn transitions. In this work, we propose
to enhance SLU in multi-turn dialogs, employing a context-aware hierarchical
BERT fusion Network (CaBERT-SLU) to not only discern context information within
a dialog but also jointly identify multiple dialog acts and slots in each
utterance. Experimental results show that our approach reaches new
state-of-the-art (SOTA) performances in two complicated multi-turn dialogue
datasets with considerable improvements compared with previous methods, which
only consider single utterances for multiple intents and slot filling.