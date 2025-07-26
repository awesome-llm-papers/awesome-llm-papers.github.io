---
layout: publication
title: An Empirical Study Of Example Forgetting During Deep Neural Network Learning
authors: Mariya Toneva, Alessandro Sordoni, Remi Tachet Des Combes, Adam Trischler,
  Yoshua Bengio, Geoffrey J. Gordon
conference: Arxiv
year: 2018
bibkey: toneva2018empirical
citations: 198
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1812.05159'}]
tags: ["Evaluation", "Training Techniques"]
short_authors: Toneva et al.
---
Inspired by the phenomenon of catastrophic forgetting, we investigate the
learning dynamics of neural networks as they train on single classification
tasks. Our goal is to understand whether a related phenomenon occurs when data
does not undergo a clear distributional shift. We define a `forgetting event'
to have occurred when an individual training example transitions from being
classified correctly to incorrectly over the course of learning. Across several
benchmark data sets, we find that: (i) certain examples are forgotten with high
frequency, and some not at all; (ii) a data set's (un)forgettable examples
generalize across neural architectures; and (iii) based on forgetting dynamics,
a significant fraction of examples can be omitted from the training data set
while still maintaining state-of-the-art generalization performance.