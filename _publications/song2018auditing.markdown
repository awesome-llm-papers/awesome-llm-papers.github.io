---
layout: publication
title: Auditing Data Provenance In Text-generation Models
authors: Congzheng Song, Vitaly Shmatikov
conference: Proceedings of the 25th ACM SIGKDD International Conference on Knowledge
  Discovery &amp; Data Mining
year: 2019
bibkey: song2018auditing
citations: 165
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1811.00513'}]
tags: ["KDD"]
short_authors: Congzheng Song, Vitaly Shmatikov
---
To help enforce data-protection regulations such as GDPR and detect
unauthorized uses of personal data, we develop a new *model auditing*
technique that helps users check if their data was used to train a machine
learning model. We focus on auditing deep-learning models that generate
natural-language text, including word prediction and dialog generation. These
models are at the core of popular online services and are often trained on
personal data such as users' messages, searches, chats, and comments.
  We design and evaluate a black-box auditing method that can detect, with very
few queries to a model, if a particular user's texts were used to train it
(among thousands of other users). We empirically show that our method can
successfully audit well-generalized models that are not overfitted to the
training data. We also analyze how text-generation models memorize word
sequences and explain why this memorization makes them amenable to auditing.