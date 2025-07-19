---
layout: publication
title: 'Consultantbert: Fine-tuned Siamese Sentence-bert For Matching Jobs And Job
  Seekers'
authors: Lavi Dor, Medentsiy Volodymyr, Graus David
conference: Proceedings of the 2019 Conference on Empirical Methods in Natural Language
  Processing and the 9th International Joint Conference on Natural Language Processing
  (EMNLP-IJCNLP)
year: 2021
bibkey: lavi2021consultantbert
citations: 4978
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2109.06501'}]
tags: [Training Techniques, EMNLP, BERT, Model Architecture, Reinforcement Learning,
  Fine Tuning, Datasets]
---
In this paper we focus on constructing useful embeddings of textual
information in vacancies and resumes, which we aim to incorporate as features
into job to job seeker matching models alongside other features. We explain our
task where noisy data from parsed resumes, heterogeneous nature of the
different sources of data, and crosslinguality and multilinguality present
domain-specific challenges.
  We address these challenges by fine-tuning a Siamese Sentence-BERT (SBERT)
model, which we call conSultantBERT, using a large-scale, real-world, and high
quality dataset of over 270,000 resume-vacancy pairs labeled by our staffing
consultants. We show how our fine-tuned model significantly outperforms
unsupervised and supervised baselines that rely on TF-IDF-weighted feature
vectors and BERT embeddings. In addition, we find our model successfully
matches cross-lingual and multilingual textual content.