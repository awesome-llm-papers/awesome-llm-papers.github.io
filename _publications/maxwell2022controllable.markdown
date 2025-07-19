---
layout: publication
title: Controllable Image Captioning
authors: Maxwell Luka
conference: Lecture Notes in Computer Science
year: 2022
bibkey: maxwell2022controllable
citations: 50
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2204.13324'}]
tags: [Interpretability And Explainability, Tools, Transformer, Model Architecture,
  Datasets]
---
State-of-the-art image captioners can generate accurate sentences to describe
images in a sequence to sequence manner without considering the controllability
and interpretability. This, however, is far from making image captioning widely
used as an image can be interpreted in infinite ways depending on the target
and the context at hand. Achieving controllability is important especially when
the image captioner is used by different people with different way of
interpreting the images. In this paper, we introduce a novel framework for
image captioning which can generate diverse descriptions by capturing the
co-dependence between Part-Of-Speech tags and semantics. Our model decouples
direct dependence between successive variables. In this way, it allows the
decoder to exhaustively search through the latent Part-Of-Speech choices, while
keeping decoding speed proportional to the size of the POS vocabulary. Given a
control signal in the form of a sequence of Part-Of-Speech tags, we propose a
method to generate captions through a Transformer network, which predicts words
based on the input Part-Of-Speech tag sequences. Experiments on publicly
available datasets show that our model significantly outperforms
state-of-the-art methods on generating diverse image captions with high
qualities.