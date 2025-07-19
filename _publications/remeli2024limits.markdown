---
layout: publication
title: Limits To Predicting Online Speech Using Large Language Models
authors: Remeli Mina, Hardt Moritz, Williamson Robert C.
conference: PLOS Digital Health
year: 2024
bibkey: remeli2024limits
citations: 81
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2407.12850'}]
tags: [Security, Prompting, ALT, Reinforcement Learning, Alt]
---
We study the predictability of online speech on social media, and whether
predictability improves with information outside a user's own posts. Recent
theoretical results suggest that posts from a user's social circle are as
predictive of the user's future posts as that of the user's past posts.
Motivated by the success of large language models, we empirically test this
hypothesis. We define predictability as a measure of the model's uncertainty,
i.e., its negative log-likelihood on future tokens given context. As the basis
of our study, we collect 10M tweets for ``tweet-tuning'' base models and a
further 6.25M posts from more than five thousand X (previously Twitter) users
and their peers. Across four large language models ranging in size from 1.5
billion to 70 billion parameters, we find that predicting a user's posts from
their peers' posts performs poorly. Moreover, the value of the user's own posts
for prediction is consistently higher than that of their peers'. We extend our
investigation with a detailed analysis on what's learned in-context and the
robustness of our findings. From context, base models learn to correctly
predict @-mentions and hashtags. Moreover, our results replicate if instead of
prompting the model with additional context, we finetune on it. Across the
board, we find that predicting the posts of individual users remains hard.