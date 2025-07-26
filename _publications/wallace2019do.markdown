---
layout: publication
title: Do NLP Models Know Numbers? Probing Numeracy In Embeddings
authors: Eric Wallace, Yizhong Wang, Sujian Li, Sameer Singh, Matt Gardner
conference: Proceedings of the 2019 Conference on Empirical Methods in Natural Language
  Processing and the 9th International Joint Conference on Natural Language Processing
  (EMNLP-IJCNLP)
year: 2019
bibkey: wallace2019do
citations: 226
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1909.07940'}]
tags: ["EMNLP"]
short_authors: Wallace et al.
---
The ability to understand and work with numbers (numeracy) is critical for
many complex reasoning tasks. Currently, most NLP models treat numbers in text
in the same way as other tokens---they embed them as distributed vectors. Is
this enough to capture numeracy? We begin by investigating the numerical
reasoning capabilities of a state-of-the-art question answering model on the
DROP dataset. We find this model excels on questions that require numerical
reasoning, i.e., it already captures numeracy. To understand how this
capability emerges, we probe token embedding methods (e.g., BERT, GloVe) on
synthetic list maximum, number decoding, and addition tasks. A surprising
degree of numeracy is naturally present in standard embeddings. For example,
GloVe and word2vec accurately encode magnitude for numbers up to 1,000.
Furthermore, character-level embeddings are even more precise---ELMo captures
numeracy the best for all pre-trained methods---but BERT, which uses sub-word
units, is less exact.