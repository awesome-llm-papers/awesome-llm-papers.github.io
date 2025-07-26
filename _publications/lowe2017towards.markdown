---
layout: publication
title: 'Towards An Automatic Turing Test: Learning To Evaluate Dialogue Responses'
authors: Ryan Lowe, Michael Noseworthy, Iulian V. Serban, Nicolas Angelard-gontier,
  Yoshua Bengio, Joelle Pineau
conference: 'Proceedings of the 55th Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)'
year: 2017
bibkey: lowe2017towards
citations: 362
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1708.07149'}]
tags: ["Evaluation", "Training Techniques"]
short_authors: Lowe et al.
---
Automatically evaluating the quality of dialogue responses for unstructured
domains is a challenging problem. Unfortunately, existing automatic evaluation
metrics are biased and correlate very poorly with human judgements of response
quality. Yet having an accurate automatic evaluation procedure is crucial for
dialogue research, as it allows rapid prototyping and testing of new models
with fewer expensive human evaluations. In response to this challenge, we
formulate automatic dialogue evaluation as a learning problem. We present an
evaluation model (ADEM) that learns to predict human-like scores to input
responses, using a new dataset of human response scores. We show that the ADEM
model's predictions correlate significantly, and at a level much higher than
word-overlap metrics such as BLEU, with human judgements at both the utterance
and system-level. We also show that ADEM can generalize to evaluating dialogue
models unseen during training, an important step for automatic dialogue
evaluation.