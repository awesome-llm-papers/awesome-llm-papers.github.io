---
layout: publication
title: Structured Reordering For Modeling Latent Alignments In Sequence Transduction
authors: Bailin Wang, Mirella Lapata, Ivan Titov
conference: 2021 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2021
bibkey: wang2021structured
citations: 71
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2106.03257'}]
tags: ["CVPR"]
short_authors: Bailin Wang, Mirella Lapata, Ivan Titov
---
Despite success in many domains, neural models struggle in settings where
train and test examples are drawn from different distributions. In particular,
in contrast to humans, conventional sequence-to-sequence (seq2seq) models fail
to generalize systematically, i.e., interpret sentences representing novel
combinations of concepts (e.g., text segments) seen in training. Traditional
grammar formalisms excel in such settings by implicitly encoding alignments
between input and output segments, but are hard to scale and maintain. Instead
of engineering a grammar, we directly model segment-to-segment alignments as
discrete structured latent variables within a neural seq2seq model. To
efficiently explore the large space of alignments, we introduce a reorder-first
align-later framework whose central component is a neural reordering module
producing \{\it separable\} permutations. We present an efficient dynamic
programming algorithm performing exact marginal inference of separable
permutations, and, thus, enabling end-to-end differentiable training of our
model. The resulting seq2seq model exhibits better systematic generalization
than standard models on synthetic problems and NLP tasks (i.e., semantic
parsing and machine translation).