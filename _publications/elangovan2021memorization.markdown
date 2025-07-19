---
layout: publication
title: 'Memorization Vs. Generalization: Quantifying Data Leakage In NLP Performance
  Evaluation'
authors: Elangovan Aparna, He Jiayuan, Verspoor Karin
conference: 'Proceedings of the 16th Conference of the European Chapter of the Association
  for Computational Linguistics: Main Volume'
year: 2021
bibkey: elangovan2021memorization
citations: 53
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2102.01818'}]
tags: [Training Techniques, Datasets, Evaluation, ACL, EACL, Reinforcement Learning]
---
Public datasets are often used to evaluate the efficacy and generalizability
of state-of-the-art methods for many tasks in natural language processing
(NLP). However, the presence of overlap between the train and test datasets can
lead to inflated results, inadvertently evaluating the model's ability to
memorize and interpreting it as the ability to generalize. In addition, such
data sets may not provide an effective indicator of the performance of these
methods in real world scenarios. We identify leakage of training data into test
data on several publicly available datasets used to evaluate NLP tasks,
including named entity recognition and relation extraction, and study them to
assess the impact of that leakage on the model's ability to memorize versus
generalize.