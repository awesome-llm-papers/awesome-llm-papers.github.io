---
layout: publication
title: Relational Recurrent Neural Networks
authors: Adam Santoro, Ryan Faulkner, David Raposo, Jack Rae, Mike Chrzanowski, Theophane
  Weber, Daan Wierstra, Oriol Vinyals, Razvan Pascanu, Timothy Lillicrap
conference: Arxiv
year: 2018
bibkey: santoro2018relational
citations: 139
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1806.01822'}]
tags: ["Datasets", "Evaluation", "Reinforcement Learning", "Time Series"]
short_authors: Santoro et al.
---
Memory-based neural networks model temporal data by leveraging an ability to
remember information for long periods. It is unclear, however, whether they
also have an ability to perform complex relational reasoning with the
information they remember. Here, we first confirm our intuitions that standard
memory architectures may struggle at tasks that heavily involve an
understanding of the ways in which entities are connected -- i.e., tasks
involving relational reasoning. We then improve upon these deficits by using a
new memory module -- a \textit\{Relational Memory Core\} (RMC) -- which employs
multi-head dot product attention to allow memories to interact. Finally, we
test the RMC on a suite of tasks that may profit from more capable relational
reasoning across sequential information, and show large gains in RL domains
(e.g. Mini PacMan), program evaluation, and language modeling, achieving
state-of-the-art results on the WikiText-103, Project Gutenberg, and GigaWord
datasets.