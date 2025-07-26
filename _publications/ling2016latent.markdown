---
layout: publication
title: Latent Predictor Networks For Code Generation
authors: "Wang Ling, Edward Grefenstette, Karl Moritz Hermann, Tom\xE1\u0161 Ko\u010D\
  isk\xFD, Andrew Senior, Fumin Wang, Phil Blunsom"
conference: 'Proceedings of the 54th Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)'
year: 2016
bibkey: ling2016latent
citations: 298
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1603.06744'}]
tags: ["Llm For Code", "Model Architecture", "Tools"]
short_authors: Ling et al.
---
Many language generation tasks require the production of text conditioned on
both structured and unstructured inputs. We present a novel neural network
architecture which generates an output sequence conditioned on an arbitrary
number of input functions. Crucially, our approach allows both the choice of
conditioning context and the granularity of generation, for example characters
or tokens, to be marginalised, thus permitting scalable and effective training.
Using this framework, we address the problem of generating programming code
from a mixed natural language and structured specification. We create two new
data sets for this paradigm derived from the collectible trading card games
Magic the Gathering and Hearthstone. On these, and a third preexisting corpus,
we demonstrate that marginalising multiple predictors allows our model to
outperform strong benchmarks.