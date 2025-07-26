---
layout: publication
title: Can Neural Networks Understand Logical Entailment?
authors: Richard Evans, David Saxton, David Amos, Pushmeet Kohli, Edward Grefenstette
conference: Arxiv
year: 2018
bibkey: evans2018can
citations: 63
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1802.08535'}]
tags: ["Model Architecture"]
short_authors: Evans et al.
---
We introduce a new dataset of logical entailments for the purpose of
measuring models' ability to capture and exploit the structure of logical
expressions against an entailment prediction task. We use this task to compare
a series of architectures which are ubiquitous in the sequence-processing
literature, in addition to a new model class---PossibleWorldNets---which
computes entailment as a "convolution over possible worlds". Results show that
convolutional networks present the wrong inductive bias for this class of
problems relative to LSTM RNNs, tree-structured neural networks outperform LSTM
RNNs due to their enhanced ability to exploit the syntax of logic, and
PossibleWorldNets outperform all benchmarks.