---
layout: publication
title: Hierarchical Learning For Generation With Long Source Sequences
authors: Tobias Rohde, Xiaoxia Wu, Yinhan Liu
conference: Arxiv
year: 2021
citations: 38
bibkey: rohde2021hierarchical
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2104.07545'}]
tags: [Training Techniques, Transformer, RAG, Pre-Training, Attention Mechanism, WMT,
  Arxiv, Model Architecture]
---
One of the challenges for current sequence to sequence (seq2seq) models is
processing long sequences, such as those in summarization and document level
machine translation tasks. These tasks require the model to reason at the token
level as well as the sentence and paragraph level. We design and study a new
Hierarchical Attention Transformer-based architecture (HAT) that outperforms
standard Transformers on several sequence to sequence tasks. Furthermore, our
model achieves state-of-the-art ROUGE scores on four summarization tasks,
including PubMed, arXiv, CNN/DM, SAMSum, and AMI. Our model outperforms
document-level machine translation baseline on the WMT20 English to German
translation task. We investigate what the hierarchical layers learn by
visualizing the hierarchical encoder-decoder attention. Finally, we study
hierarchical learning on encoder-only pre-training and analyze its performance
on classification tasks.