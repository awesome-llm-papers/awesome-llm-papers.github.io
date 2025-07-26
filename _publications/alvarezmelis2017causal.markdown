---
layout: publication
title: A Causal Framework For Explaining The Predictions Of Black-box Sequence-to-sequence
  Models
authors: David Alvarez-melis, Tommi S. Jaakkola
conference: Proceedings of the 2017 Conference on Empirical Methods in Natural Language
  Processing
year: 2017
bibkey: alvarezmelis2017causal
citations: 176
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1707.01943'}]
tags: ["EMNLP"]
short_authors: David Alvarez-melis, Tommi S. Jaakkola
---
We interpret the predictions of any black-box structured input-structured
output model around a specific input-output pair. Our method returns an
"explanation" consisting of groups of input-output tokens that are causally
related. These dependencies are inferred by querying the black-box model with
perturbed inputs, generating a graph over tokens from the responses, and
solving a partitioning problem to select the most relevant components. We focus
the general approach on sequence-to-sequence problems, adopting a variational
autoencoder to yield meaningful input perturbations. We test our method across
several NLP sequence generation tasks.