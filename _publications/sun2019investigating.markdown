---
layout: publication
title: Investigating Prior Knowledge For Challenging Chinese Machine Reading Comprehension
authors: Sun et al.
conference: Transactions of the Association for Computational Linguistics
year: 2019
bibkey: sun2019investigating
citations: 55
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1904.09679'}]
tags: [Tools, TACL, ACL, RAG, Datasets, Reinforcement Learning]
---
Machine reading comprehension tasks require a machine reader to answer
questions relevant to the given document. In this paper, we present the first
free-form multiple-Choice Chinese machine reading Comprehension dataset (C^3),
containing 13,369 documents (dialogues or more formally written mixed-genre
texts) and their associated 19,577 multiple-choice free-form questions
collected from Chinese-as-a-second-language examinations.
  We present a comprehensive analysis of the prior knowledge (i.e., linguistic,
domain-specific, and general world knowledge) needed for these real-world
problems. We implement rule-based and popular neural methods and find that
there is still a significant performance gap between the best performing model
(68.5%) and human readers (96.0%), especially on problems that require prior
knowledge. We further study the effects of distractor plausibility and data
augmentation based on translated relevant datasets for English on model
performance. We expect C^3 to present great challenges to existing systems as
answering 86.8% of questions requires both knowledge within and beyond the
accompanying document, and we hope that C^3 can serve as a platform to study
how to leverage various kinds of prior knowledge to better understand a given
written or orally oriented text. C^3 is available at https://dataset.org/c3/.