---
layout: publication
title: Word-level Representation From Bytes For Language Modeling
authors: Lee Chu-tak, Guo Qipeng, Qiu Xipeng
conference: 'Proceedings of the 2016 Conference of the North American Chapter of the
  Association for Computational Linguistics: Human Language Technologies'
year: 2022
bibkey: lee2022word
citations: 61
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2211.12677'}]
tags: [Ethics And Bias, Model Architecture, Time Series, BERT, Tokenization, Evaluation,
  ACL, NAACL, Language Modeling, Attention Mechanism, Large Scale Training]
---
Modern language models mostly take sub-words as input, a design that balances
the trade-off between vocabulary size, number of parameters, and performance.
However, sub-word tokenization still has disadvantages like not being robust to
noise and difficult to generalize to new languages. Also, the current trend of
scaling up models reveals that larger models require larger embeddings but that
makes parallelization hard. Previous work on image classification proves
splitting raw input into a sequence of chucks is a strong, model-agnostic
inductive bias. Based on this observation, we rethink the existing
character-aware method that takes character-level inputs but makes word-level
sequence modeling and prediction. We overhaul this method by introducing a
cross-attention network that builds word-level representation directly from
bytes, and a sub-word level prediction based on word-level hidden states to
avoid the time and space requirement of word-level prediction. With these two
improvements combined, we have a token free model with slim input embeddings
for downstream tasks. We name our method Byte2Word and perform evaluations on
language modeling and text classification. Experiments show that Byte2Word is
on par with the strong sub-word baseline BERT but only takes up 10% of
embedding size. We further test our method on synthetic noise and cross-lingual
transfer and find it competitive to baseline methods on both settings.