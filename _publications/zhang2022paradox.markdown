---
layout: publication
title: On The Paradox Of Learning To Reason From Data
authors: Honghua Zhang, Liunian Harold Li, Tao Meng, Kai-wei Chang, Guy Van Den Broeck
conference: Arxiv
year: 2022
citations: 17
bibkey: zhang2022paradox
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2205.11502'}]
tags: [Interpretability and Explainability, Model Architecture, BERT]
---
Logical reasoning is needed in a wide range of NLP tasks. Can a BERT model be
trained end-to-end to solve logical reasoning problems presented in natural
language? We attempt to answer this question in a confined problem space where
there exists a set of parameters that perfectly simulates logical reasoning. We
make observations that seem to contradict each other: BERT attains near-perfect
accuracy on in-distribution test examples while failing to generalize to other
data distributions over the exact same problem space. Our study provides an
explanation for this paradox: instead of learning to emulate the correct
reasoning function, BERT has in fact learned statistical features that
inherently exist in logical reasoning problems. We also show that it is
infeasible to jointly remove statistical features from data, illustrating the
difficulty of learning to reason in general. Our result naturally extends to
other neural models and unveils the fundamental difference between learning to
reason and learning to achieve high performance on NLP benchmarks using
statistical features.