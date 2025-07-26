---
layout: publication
title: Scaling Laws For Neural Language Models
authors: [jared Kaplan, sam Mccandlish, tom Henighan, tom B. Brown, benjamin Chess,
  rewon Child, scott Gray, alec Radford, jeffrey Wu, dario Amodei]
conference: Arxiv
year: 2020
bibkey: jared2020scaling
citations: 1236
additional_links: [{name: Paper, url: 'http://arxiv.org/abs/2001.08361v1'}]
tags: ["Efficiency", "Training Techniques"]
short_authors: Kaplan et al.
---
We study empirical scaling laws for language model performance on the
cross-entropy loss. The loss scales as a power-law with model size, dataset
size, and the amount of compute used for training, with some trends spanning
more than seven orders of magnitude. Other architectural details such as
network width or depth have minimal effects within a wide range. Simple
equations govern the dependence of overfitting on model/dataset size and the
dependence of training speed on model size. These relationships allow us to
determine the optimal allocation of a fixed compute budget. Larger models are
significantly more sample-efficient, such that optimally compute-efficient
training involves training very large models on a relatively modest amount of
data and stopping significantly before convergence.