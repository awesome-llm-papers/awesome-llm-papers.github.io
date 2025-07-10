---
layout: publication
title: Relevance-guided Supervision For Openqa With Colbert
authors: Omar Khattab, Christopher Potts, Matei Zaharia
conference: Transactions of the Association for Computational Linguistics
year: 2020
citations: 28
bibkey: khattab2020relevance
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2007.00814'}]
tags: [BERT, Training Techniques, Model Architecture]
---
Systems for Open-Domain Question Answering (OpenQA) generally depend on a
retriever for finding candidate passages in a large corpus and a reader for
extracting answers from those passages. In much recent work, the retriever is a
learned component that uses coarse-grained vector representations of questions
and passages. We argue that this modeling choice is insufficiently expressive
for dealing with the complexity of natural language questions. To address this,
we define ColBERT-QA, which adapts the scalable neural retrieval model ColBERT
to OpenQA. ColBERT creates fine-grained interactions between questions and
passages. We propose an efficient weak supervision strategy that iteratively
uses ColBERT to create its own training data. This greatly improves OpenQA
retrieval on Natural Questions, SQuAD, and TriviaQA, and the resulting system
attains state-of-the-art extractive OpenQA performance on all three datasets.