---
layout: publication
title: Sequence-to-sequence Learning As Beam-search Optimization
authors: Sam Wiseman, Alexander M. Rush
conference: Proceedings of the 2016 Conference on Empirical Methods in Natural Language
  Processing
year: 2016
bibkey: wiseman2016sequence
citations: 463
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1606.02960'}]
tags: ["EMNLP", "Model Architecture", "Training Techniques"]
short_authors: Sam Wiseman, Alexander M. Rush
---
Sequence-to-Sequence (seq2seq) modeling has rapidly become an important
general-purpose NLP tool that has proven effective for many text-generation and
sequence-labeling tasks. Seq2seq builds on deep neural language modeling and
inherits its remarkable accuracy in estimating local, next-word distributions.
In this work, we introduce a model and beam-search training scheme, based on
the work of Daume III and Marcu (2005), that extends seq2seq to learn global
sequence scores. This structured approach avoids classical biases associated
with local training and unifies the training loss with the test-time usage,
while preserving the proven model architecture of seq2seq and its efficient
training approach. We show that our system outperforms a highly-optimized
attention-based seq2seq system and other baselines on three different sequence
to sequence tasks: word ordering, parsing, and machine translation.