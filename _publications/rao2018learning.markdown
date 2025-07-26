---
layout: publication
title: 'Learning To Ask Good Questions: Ranking Clarification Questions Using Neural
  Expected Value Of Perfect Information'
authors: "Sudha Rao, Hal Daum\xE9"
conference: 'Proceedings of the 56th Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)'
year: 2018
bibkey: rao2018learning
citations: 149
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1805.04655'}]
tags: ["Datasets"]
short_authors: "Sudha Rao, Hal Daum\xE9"
---
Inquiry is fundamental to communication, and machines cannot effectively
collaborate with humans unless they can ask questions. In this work, we build a
neural network model for the task of ranking clarification questions. Our model
is inspired by the idea of expected value of perfect information: a good
question is one whose expected answer will be useful. We study this problem
using data from StackExchange, a plentiful online resource in which people
routinely ask clarifying questions to posts so that they can better offer
assistance to the original poster. We create a dataset of clarification
questions consisting of ~77K posts paired with a clarification question (and
answer) from three domains of StackExchange: askubuntu, unix and superuser. We
evaluate our model on 500 samples of this dataset against expert human
judgments and demonstrate significant improvements over controlled baselines.