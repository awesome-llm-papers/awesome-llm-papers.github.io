---
layout: publication
title: Learning An Unreferenced Metric For Online Dialogue Evaluation
authors: Koustuv Sinha, Prasanna Parthasarathi, Jasmine Wang, Ryan Lowe, William L.
  Hamilton, Joelle Pineau
conference: Proceedings of the 58th Annual Meeting of the Association for Computational
  Linguistics
year: 2020
bibkey: sinha2020learning
citations: 66
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2005.00583'}]
tags: ["Evaluation"]
short_authors: Sinha et al.
---
Evaluating the quality of a dialogue interaction between two agents is a
difficult task, especially in open-domain chit-chat style dialogue. There have
been recent efforts to develop automatic dialogue evaluation metrics, but most
of them do not generalize to unseen datasets and/or need a human-generated
reference response during inference, making it infeasible for online
evaluation. Here, we propose an unreferenced automated evaluation metric that
uses large pre-trained language models to extract latent representations of
utterances, and leverages the temporal transitions that exist between them. We
show that our model achieves higher correlation with human annotations in an
online setting, while not requiring true responses for comparison during
inference.