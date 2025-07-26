---
layout: publication
title: Good-enough Compositional Data Augmentation
authors: Jacob Andreas
conference: Proceedings of the 58th Annual Meeting of the Association for Computational
  Linguistics
year: 2020
bibkey: andreas2019good
citations: 195
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1904.09545'}]
tags: ["Datasets", "Training Techniques"]
short_authors: Jacob Andreas
---
We propose a simple data augmentation protocol aimed at providing a
compositional inductive bias in conditional and unconditional sequence models.
Under this protocol, synthetic training examples are constructed by taking real
training examples and replacing (possibly discontinuous) fragments with other
fragments that appear in at least one similar environment. The protocol is
model-agnostic and useful for a variety of tasks. Applied to neural
sequence-to-sequence models, it reduces error rate by as much as 87% on
diagnostic tasks from the SCAN dataset and 16% on a semantic parsing task.
Applied to n-gram language models, it reduces perplexity by roughly 1% on small
corpora in several languages.