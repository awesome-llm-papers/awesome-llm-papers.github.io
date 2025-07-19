---
layout: publication
title: Will It Unblend?
authors: Pinter Yuval, Jacobs Cassandra L., Eisenstein Jacob
conference: Cell
year: 2020
bibkey: pinter2020will
citations: 168
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2009.09123'}]
tags: [Training Techniques, Alt, BERT, Model Architecture, Reinforcement Learning,
  Datasets]
---
Natural language processing systems often struggle with out-of-vocabulary
(OOV) terms, which do not appear in training data. Blends, such as
"innoventor", are one particularly challenging class of OOV, as they are formed
by fusing together two or more bases that relate to the intended meaning in
unpredictable manners and degrees. In this work, we run experiments on a novel
dataset of English OOV blends to quantify the difficulty of interpreting the
meanings of blends by large-scale contextual language models such as BERT. We
first show that BERT's processing of these blends does not fully access the
component meanings, leaving their contextual representations semantically
impoverished. We find this is mostly due to the loss of characters resulting
from blend formation. Then, we assess how easily different models can recognize
the structure and recover the origin of blends, and find that context-aware
embedding systems outperform character-level and context-free embeddings,
although their results are still far from satisfactory.