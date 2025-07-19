---
layout: publication
title: Dynamic Position Encoding For Transformers
authors: Zheng Joyce, Rezagholizadeh Mehdi, Passban Peyman
conference: Arxiv
year: 2022
bibkey: zheng2022dynamic
citations: 58
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2204.08142'}]
tags: [Training Techniques, Attention Mechanism, Alt, Transformer, Model Architecture,
  Reinforcement Learning, Datasets]
---
Recurrent models have been dominating the field of neural machine translation
(NMT) for the past few years. Transformers \citep\{vaswani2017attention\}, have
radically changed it by proposing a novel architecture that relies on a
feed-forward backbone and self-attention mechanism. Although Transformers are
powerful, they could fail to properly encode sequential/positional information
due to their non-recurrent nature. To solve this problem, position embeddings
are defined exclusively for each time step to enrich word information. However,
such embeddings are fixed after training regardless of the task and the word
ordering system of the source or target language.
  In this paper, we propose a novel architecture with new position embeddings
depending on the input text to address this shortcoming by taking the order of
target words into consideration. Instead of using predefined position
embeddings, our solution generates new embeddings to refine each word's
position information. Since we do not dictate the position of source tokens and
learn them in an end-to-end fashion, we refer to our method as dynamic position
encoding (DPE). We evaluated the impact of our model on multiple datasets to
translate from English into German, French, and Italian and observed meaningful
improvements in comparison to the original Transformer.