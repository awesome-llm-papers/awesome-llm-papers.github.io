---
layout: publication
title: Uncertain Natural Language Inference
authors: Chen et al.
conference: Proceedings of the 58th Annual Meeting of the Association for Computational
  Linguistics
year: 2019
bibkey: chen2019uncertain
citations: 53
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1909.03042'}]
tags: [Datasets, ACL, Training Techniques]
---
We introduce Uncertain Natural Language Inference (UNLI), a refinement of
Natural Language Inference (NLI) that shifts away from categorical labels,
targeting instead the direct prediction of subjective probability assessments.
We demonstrate the feasibility of collecting annotations for UNLI by relabeling
a portion of the SNLI dataset under a probabilistic scale, where items even
with the same categorical label differ in how likely people judge them to be
true given a premise. We describe a direct scalar regression modeling approach,
and find that existing categorically labeled NLI data can be used in
pre-training. Our best models approach human performance, demonstrating models
may be capable of more subtle inferences than the categorical bin assignment
employed in current NLI tasks.