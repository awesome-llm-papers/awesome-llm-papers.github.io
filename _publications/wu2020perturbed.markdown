---
layout: publication
title: 'Perturbed Masking: Parameter-free Probing For Analyzing And Interpreting BERT'
authors: Wu et al.
conference: Proceedings of the 58th Annual Meeting of the Association for Computational
  Linguistics
year: 2020
bibkey: wu2020perturbed
citations: 153
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2004.14786'}]
tags: [ACL, Model Architecture, BERT]
---
By introducing a small set of additional parameters, a probe learns to solve
specific linguistic tasks (e.g., dependency parsing) in a supervised manner
using feature representations (e.g., contextualized embeddings). The
effectiveness of such probing tasks is taken as evidence that the pre-trained
model encodes linguistic knowledge. However, this approach of evaluating a
language model is undermined by the uncertainty of the amount of knowledge that
is learned by the probe itself. Complementary to those works, we propose a
parameter-free probing technique for analyzing pre-trained language models
(e.g., BERT). Our method does not require direct supervision from the probing
tasks, nor do we introduce additional parameters to the probing process. Our
experiments on BERT show that syntactic trees recovered from BERT using our
method are significantly better than linguistically-uninformed baselines. We
further feed the empirically induced dependency structures into a downstream
sentiment classification task and find its improvement compatible with or even
superior to a human-designed dependency schema.