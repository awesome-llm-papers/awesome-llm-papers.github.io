---
layout: publication
title: 'Transfer Fine-tuning: A BERT Case Study'
authors: Yuki Arase, Junichi Tsujii
conference: Proceedings of the 2019 Conference on Empirical Methods in Natural Language
  Processing and the 9th International Joint Conference on Natural Language Processing
  (EMNLP-IJCNLP)
year: 2019
citations: 16
bibkey: arase2019transfer
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1909.00931'}]
tags: [Model Architecture, Fine-Tuning, TACL, Applications, ACL, BERT, Training Techniques]
---
A semantic equivalence assessment is defined as a task that assesses semantic
equivalence in a sentence pair by binary judgment (i.e., paraphrase
identification) or grading (i.e., semantic textual similarity measurement). It
constitutes a set of tasks crucial for research on natural language
understanding. Recently, BERT realized a breakthrough in sentence
representation learning (Devlin et al., 2019), which is broadly transferable to
various NLP tasks. While BERT's performance improves by increasing its model
size, the required computational power is an obstacle preventing practical
applications from adopting the technology. Herein, we propose to inject phrasal
paraphrase relations into BERT in order to generate suitable representations
for semantic equivalence assessment instead of increasing the model size.
Experiments on standard natural language understanding tasks confirm that our
method effectively improves a smaller BERT model while maintaining the model
size. The generated model exhibits superior performance compared to a larger
BERT model on semantic equivalence assessment tasks. Furthermore, it achieves
larger performance gains on tasks with limited training datasets for
fine-tuning, which is a property desirable for transfer learning.