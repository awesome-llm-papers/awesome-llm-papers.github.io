---
layout: publication
title: Do Neural Dialog Systems Use The Conversation History Effectively? An Empirical
  Study
authors: Chinnadhurai Sankar, Sandeep Subramanian, Christopher Pal, Sarath Chandar,
  Yoshua Bengio
conference: Proceedings of the 57th Annual Meeting of the Association for Computational
  Linguistics
year: 2019
bibkey: sankar2019do
citations: 115
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1906.01603'}]
tags: ["Datasets", "Model Architecture"]
short_authors: Sankar et al.
---
Neural generative models have been become increasingly popular when building
conversational agents. They offer flexibility, can be easily adapted to new
domains, and require minimal domain engineering. A common criticism of these
systems is that they seldom understand or use the available dialog history
effectively. In this paper, we take an empirical approach to understanding how
these models use the available dialog history by studying the sensitivity of
the models to artificially introduced unnatural changes or perturbations to
their context at test time. We experiment with 10 different types of
perturbations on 4 multi-turn dialog datasets and find that commonly used
neural dialog architectures like recurrent and transformer-based seq2seq models
are rarely sensitive to most perturbations such as missing or reordering
utterances, shuffling words, etc. Also, by open-sourcing our code, we believe
that it will serve as a useful diagnostic tool for evaluating dialog systems in
the future.