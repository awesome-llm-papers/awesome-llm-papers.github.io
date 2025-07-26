---
layout: publication
title: Logic-guided Data Augmentation And Regularization For Consistent Question Answering
authors: Akari Asai, Hannaneh Hajishirzi
conference: Proceedings of the 58th Annual Meeting of the Association for Computational
  Linguistics
year: 2020
bibkey: asai2020logic
citations: 63
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2004.10157'}]
tags: ["Datasets", "Training Techniques"]
short_authors: Akari Asai, Hannaneh Hajishirzi
---
Many natural language questions require qualitative, quantitative or logical
comparisons between two entities or events. This paper addresses the problem of
improving the accuracy and consistency of responses to comparison questions by
integrating logic rules and neural models. Our method leverages logical and
linguistic knowledge to augment labeled training data and then uses a
consistency-based regularizer to train the model. Improving the global
consistency of predictions, our approach achieves large improvements over
previous methods in a variety of question answering (QA) tasks including
multiple-choice qualitative reasoning, cause-effect reasoning, and extractive
machine reading comprehension. In particular, our method significantly improves
the performance of RoBERTa-based models by 1-5% across datasets. We advance the
state of the art by around 5-8% on WIQA and QuaRel and reduce consistency
violations by 58% on HotpotQA. We further demonstrate that our approach can
learn effectively from limited data.