---
layout: publication
title: Learning With Latent Language
authors: Jacob Andreas, Dan Klein, Sergey Levine
conference: 'Proceedings of the 2018 Conference of the North American Chapter of the
  Association for Computational Linguistics: Human Language Technologies, Volume 1
  (Long Papers)'
year: 2018
bibkey: andreas2017learning
citations: 82
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1711.00482'}]
tags: ["NAACL"]
short_authors: Jacob Andreas, Dan Klein, Sergey Levine
---
The named concepts and compositional operators present in natural language
provide a rich source of information about the kinds of abstractions humans use
to navigate the world. Can this linguistic background knowledge improve the
generality and efficiency of learned classifiers and control policies? This
paper aims to show that using the space of natural language strings as a
parameter space is an effective way to capture natural task structure. In a
pretraining phase, we learn a language interpretation model that transforms
inputs (e.g. images) into outputs (e.g. labels) given natural language
descriptions. To learn a new concept (e.g. a classifier), we search directly in
the space of descriptions to minimize the interpreter's loss on training
examples. Crucially, our models do not require language data to learn these
concepts: language is used only in pretraining to impose structure on
subsequent learning. Results on image classification, text editing, and
reinforcement learning show that, in all settings, models with a linguistic
parameterization outperform those without.