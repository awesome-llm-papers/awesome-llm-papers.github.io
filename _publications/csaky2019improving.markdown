---
layout: publication
title: Improving Neural Conversational Models With Entropy-based Data Filtering
authors: Richard Csaky, Patrik Purgai, Gabor Recski
conference: Proceedings of the 57th Annual Meeting of the Association for Computational
  Linguistics
year: 2019
bibkey: csaky2019improving
citations: 64
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1905.05471'}]
tags: ["Datasets", "Evaluation", "Training Techniques"]
short_authors: Richard Csaky, Patrik Purgai, Gabor Recski
---
Current neural network-based conversational models lack diversity and
generate boring responses to open-ended utterances. Priors such as persona,
emotion, or topic provide additional information to dialog models to aid
response generation, but annotating a dataset with priors is expensive and such
annotations are rarely available. While previous methods for improving the
quality of open-domain response generation focused on either the underlying
model or the training objective, we present a method of filtering dialog
datasets by removing generic utterances from training data using a simple
entropy-based approach that does not require human supervision. We conduct
extensive experiments with different variations of our method, and compare
dialog models across 17 evaluation metrics to show that training on datasets
filtered this way results in better conversational quality as chatbots learn to
output more diverse responses.