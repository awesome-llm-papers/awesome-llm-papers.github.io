---
layout: publication
title: Grounding Visual Explanations (extended Abstract)
authors: Hendricks et al.
conference: Lecture Notes in Computer Science
year: 2017
bibkey: hendricks2017grounding
citations: 84
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1711.06465'}]
tags: [Interpretability And Explainability, Training Techniques]
---
Existing models which generate textual explanations enforce task relevance
through a discriminative term loss function, but such mechanisms only weakly
constrain mentioned object parts to actually be present in the image. In this
paper, a new model is proposed for generating explanations by utilizing
localized grounding of constituent phrases in generated explanations to ensure
image relevance. Specifically, we introduce a phrase-critic model to refine
(re-score/re-rank) generated candidate explanations and employ a
relative-attribute inspired ranking loss using "flipped" phrases as negative
examples for training. At test time, our phrase-critic model takes an image and
a candidate explanation as input and outputs a score indicating how well the
candidate explanation is grounded in the image.