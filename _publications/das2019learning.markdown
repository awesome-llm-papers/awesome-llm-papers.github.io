---
layout: publication
title: Learning To Answer Subjective, Specific Product-related Queries Using Customer
  Reviews By Adversarial Domain Adaptation
authors: Das et al.
conference: Proceedings of the 25th International Conference on World Wide Web
year: 2019
bibkey: das2019learning
citations: 89
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1910.08270'}]
tags: [Training Techniques, Alt, Reinforcement Learning, Security, Fine Tuning, Datasets]
---
Online customer reviews on large-scale e-commerce websites, represent a rich
and varied source of opinion data, often providing subjective qualitative
assessments of product usage that can help potential customers to discover
features that meet their personal needs and preferences. Thus they have the
potential to automatically answer specific queries about products, and to
address the problems of answer starvation and answer augmentation on associated
consumer Q & A forums, by providing good answer alternatives. In this work, we
explore several recently successful neural approaches to modeling sentence
pairs, that could better learn the relationship between questions and ground
truth answers, and thus help infer reviews that can best answer a question or
augment a given answer. In particular, we hypothesize that our adversarial
domain adaptation-based approach, due to its ability to additionally learn
domain-invariant features from a large number of unlabeled, unpaired
question-review samples, would perform better than our proposed baselines, at
answering specific, subjective product-related queries using reviews. We
validate this hypothesis using a small gold standard dataset of question-review
pairs evaluated by human experts, significantly surpassing our chosen
baselines. Moreover, our approach, using no labeled question-review sentence
pair data for training, gives performance at par with another method utilizing
labeled question-review samples for the same task.