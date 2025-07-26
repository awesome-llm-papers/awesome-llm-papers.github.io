---
layout: publication
title: Pretrained Language Models For Sequential Sentence Classification
authors: Arman Cohan, Iz Beltagy, Daniel King, Bhavana Dalvi, Daniel S. Weld
conference: Proceedings of the 2019 Conference on Empirical Methods in Natural Language
  Processing and the 9th International Joint Conference on Natural Language Processing
  (EMNLP-IJCNLP)
year: 2019
bibkey: cohan2019pretrained
citations: 109
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1909.04054'}]
tags: ["Datasets", "EMNLP", "Model Architecture"]
short_authors: Cohan et al.
---
As a step toward better document-level understanding, we explore
classification of a sequence of sentences into their corresponding categories,
a task that requires understanding sentences in context of the document. Recent
successful models for this task have used hierarchical models to contextualize
sentence representations, and Conditional Random Fields (CRFs) to incorporate
dependencies between subsequent labels. In this work, we show that pretrained
language models, BERT (Devlin et al., 2018) in particular, can be used for this
task to capture contextual dependencies without the need for hierarchical
encoding nor a CRF. Specifically, we construct a joint sentence representation
that allows BERT Transformer layers to directly utilize contextual information
from all words in all sentences. Our approach achieves state-of-the-art results
on four datasets, including a new dataset of structured scientific abstracts.