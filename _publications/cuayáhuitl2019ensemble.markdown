---
layout: publication
title: Ensemble-based Deep Reinforcement Learning For Chatbots
authors: "Heriberto Cuay\xE1huitl, Donghyeon Lee, Seonghan Ryu, Yongjin Cho, Sungja\
  \ Choi, Satish Indurthi, Seunghak Yu, Hyungtak Choi, Inchul Hwang, Jihie Kim"
conference: Neurocomputing
year: 2019
bibkey: "cuay\xE1huitl2019ensemble"
citations: 74
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1908.10422'}]
tags: ["Reinforcement Learning"]
short_authors: "Cuay\xE1huitl et al."
---
Trainable chatbots that exhibit fluent and human-like conversations remain a
big challenge in artificial intelligence. Deep Reinforcement Learning (DRL) is
promising for addressing this challenge, but its successful application remains
an open question. This article describes a novel ensemble-based approach
applied to value-based DRL chatbots, which use finite action sets as a form of
meaning representation. In our approach, while dialogue actions are derived
from sentence clustering, the training datasets in our ensemble are derived
from dialogue clustering. The latter aim to induce specialised agents that
learn to interact in a particular style. In order to facilitate neural chatbot
training using our proposed approach, we assume dialogue data in raw text only
-- without any manually-labelled data. Experimental results using chitchat data
reveal that (1) near human-like dialogue policies can be induced, (2)
generalisation to unseen data is a difficult problem, and (3) training an
ensemble of chatbot agents is essential for improved performance over using a
single agent. In addition to evaluations using held-out data, our results are
further supported by a human evaluation that rated dialogues in terms of
fluency, engagingness and consistency -- which revealed that our proposed
dialogue rewards strongly correlate with human judgements.