---
layout: publication
title: Dialogue Response Ranking Training With Large-scale Human Feedback Data
authors: Gao et al.
conference: Proceedings of the 2020 Conference on Empirical Methods in Natural Language
  Processing (EMNLP)
year: 2020
bibkey: gao2020dialogue
citations: 60
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2009.06978'}]
tags: [RAG, EMNLP, Training Techniques, GPT, Agentic, Evaluation, Model Architecture,
  Reinforcement Learning, Large Scale Training, Datasets]
---
Existing open-domain dialog models are generally trained to minimize the
perplexity of target human responses. However, some human replies are more
engaging than others, spawning more followup interactions. Current
conversational models are increasingly capable of producing turns that are
context-relevant, but in order to produce compelling agents, these models need
to be able to predict and optimize for turns that are genuinely engaging. We
leverage social media feedback data (number of replies and upvotes) to build a
large-scale training dataset for feedback prediction. To alleviate possible
distortion between the feedback and engagingness, we convert the ranking
problem to a comparison of response pairs which involve few confounding
factors. We trained DialogRPT, a set of GPT-2 based models on 133M pairs of
human feedback data and the resulting ranker outperformed several baselines.
Particularly, our ranker outperforms the conventional dialog perplexity
baseline with a large margin on predicting Reddit feedback. We finally combine
the feedback prediction models and a human-like scoring model to rank the
machine-generated dialog responses. Crowd-sourced human evaluation shows that
our ranking method correlates better with real human preferences than baseline
models.