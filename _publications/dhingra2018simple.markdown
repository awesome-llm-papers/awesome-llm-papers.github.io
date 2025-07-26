---
layout: publication
title: Simple And Effective Semi-supervised Question Answering
authors: Bhuwan Dhingra, Danish Pruthi, Dheeraj Rajagopal
conference: 'Proceedings of the 2018 Conference of the North American Chapter of the
  Association for Computational Linguistics: Human Language Technologies, Volume 2
  (Short Papers)'
year: 2018
bibkey: dhingra2018simple
citations: 69
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1804.00720'}]
tags: ["NAACL", "Training Techniques"]
short_authors: Bhuwan Dhingra, Danish Pruthi, Dheeraj Rajagopal
---
Recent success of deep learning models for the task of extractive Question
Answering (QA) is hinged on the availability of large annotated corpora.
However, large domain specific annotated corpora are limited and expensive to
construct. In this work, we envision a system where the end user specifies a
set of base documents and only a few labelled examples. Our system exploits the
document structure to create cloze-style questions from these base documents;
pre-trains a powerful neural network on the cloze style questions; and further
fine-tunes the model on the labeled examples. We evaluate our proposed system
across three diverse datasets from different domains, and find it to be highly
effective with very little labeled data. We attain more than 50% F1 score on
SQuAD and TriviaQA with less than a thousand labelled examples. We are also
releasing a set of 3.2M cloze-style questions for practitioners to use while
building QA systems.