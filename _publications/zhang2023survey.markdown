---
layout: publication
title: A Survey On Incremental Update For Neural Recommender Systems
authors: Zhang Peiyan, Kim Sunghun
conference: ACM Computing Surveys
year: 2023
bibkey: zhang2023survey
citations: 637
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2303.02851'}]
tags: [Training Techniques, Alt, Evaluation, Survey Paper, Applications]
---
Recommender Systems (RS) aim to provide personalized suggestions of items for
users against consumer over-choice. Although extensive research has been
conducted to address different aspects and challenges of RS, there still exists
a gap between academic research and industrial applications. Specifically, most
of the existing models still work in an offline manner, in which the
recommender is trained on a large static training set and evaluated on a very
restrictive testing set in a one-time process. RS will stay unchanged until the
next batch retrain is performed. We frame such RS as Batch Update Recommender
Systems (BURS). In reality, they have to face the challenges where RS are
expected to be instantly updated with new data streaming in, and generate
updated recommendations for current user activities based on the newly arrived
data. We frame such RS as Incremental Update Recommender Systems (IURS).
  In this article, we offer a systematic survey of incremental update for
neural recommender systems. We begin the survey by introducing key concepts and
formulating the task of IURS. We then illustrate the challenges in IURS
compared with traditional BURS. Afterwards, we detail the introduction of
existing literature and evaluation issues. We conclude the survey by outlining
some prominent open research issues in this area.