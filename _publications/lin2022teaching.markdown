---
layout: publication
title: Teaching Models To Express Their Uncertainty In Words
authors: Stephanie Lin, Jacob Hilton, Owain Evans
conference: Arxiv
year: 2022
citations: 43
bibkey: lin2022teaching
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2205.14334'}]
tags: [GPT, Model Architecture]
---
We show that a GPT-3 model can learn to express uncertainty about its own
answers in natural language -- without use of model logits. When given a
question, the model generates both an answer and a level of confidence (e.g.
"90% confidence" or "high confidence"). These levels map to probabilities that
are well calibrated. The model also remains moderately calibrated under
distribution shift, and is sensitive to uncertainty in its own answers, rather
than imitating human examples. To our knowledge, this is the first time a model
has been shown to express calibrated uncertainty about its own answers in
natural language. For testing calibration, we introduce the CalibratedMath
suite of tasks. We compare the calibration of uncertainty expressed in words
("verbalized probability") to uncertainty extracted from model logits. Both
kinds of uncertainty are capable of generalizing calibration under distribution
shift. We also provide evidence that GPT-3's ability to generalize calibration
depends on pre-trained latent representations that correlate with epistemic
uncertainty over its answers.