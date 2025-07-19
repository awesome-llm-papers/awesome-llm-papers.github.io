---
layout: publication
title: Practical Annotation Strategies For Question Answering Datasets
authors: Kratzwald et al.
conference: Proceedings of the 23rd annual international ACM SIGIR conference on Research
  and development in information retrieval
year: 2020
bibkey: kratzwald2020practical
citations: 67
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2003.03235'}]
tags: [Alt, Training Techniques, Datasets, SIGIR]
---
Annotating datasets for question answering (QA) tasks is very costly, as it
requires intensive manual labor and often domain-specific knowledge. Yet
strategies for annotating QA datasets in a cost-effective manner are scarce. To
provide a remedy for practitioners, our objective is to develop heuristic rules
for annotating a subset of questions, so that the annotation cost is reduced
while maintaining both in- and out-of-domain performance. For this, we conduct
a large-scale analysis in order to derive practical recommendations. First, we
demonstrate experimentally that more training samples contribute often only to
a higher in-domain test-set performance, but do not help the model in
generalizing to unseen datasets. Second, we develop a model-guided annotation
strategy: it makes a recommendation with regard to which subset of samples
should be annotated. Its effectiveness is demonstrated in a case study based on
domain customization of QA to a clinical setting. Here, remarkably, annotating
a stratified subset with only 1.2% of the original training set achieves 97.7%
of the performance as if the complete dataset was annotated. Hence, the
labeling effort can be reduced immensely. Altogether, our work fulfills a
demand in practice when labeling budgets are limited and where thus
recommendations are needed for annotating QA datasets more cost-effectively.