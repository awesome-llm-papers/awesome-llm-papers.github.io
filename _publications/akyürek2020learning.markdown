---
layout: publication
title: Learning To Recombine And Resample Data For Compositional Generalization
authors: "Ekin Aky\xFCrek, Afra Feyza Aky\xFCrek, Jacob Andreas"
conference: Arxiv
year: 2020
citations: 40
bibkey: "aky\xFCrek2020learning"
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2010.03706'}]
tags: [Reinforcement Learning, Training Techniques, RAG]
---
Flexible neural sequence models outperform grammar- and automaton-based
counterparts on a variety of tasks. However, neural models perform poorly in
settings requiring compositional generalization beyond the training data --
particularly to rare or unseen subsequences. Past work has found symbolic
scaffolding (e.g. grammars or automata) essential in these settings. We
describe R&R, a learned data augmentation scheme that enables a large category
of compositional generalizations without appeal to latent symbolic structure.
R&R has two components: recombination of original training examples via a
prototype-based generative model and resampling of generated examples to
encourage extrapolation. Training an ordinary neural sequence model on a
dataset augmented with recombined and resampled examples significantly improves
generalization in two language processing problems -- instruction following
(SCAN) and morphological analysis (SIGMORPHON 2018) -- where R&R enables
learning of new constructions and tenses from as few as eight initial examples.