---
layout: publication
title: 'Sticking To The Facts: Confident Decoding For Faithful Data-to-text Generation'
authors: Ran Tian, Shashi Narayan, Thibault Sellam, Ankur P. Parikh
conference: Arxiv
year: 2019
citations: 57
bibkey: tian2019sticking
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1910.08684'}]
tags: [Language Modeling, Reinforcement Learning, Tools, Training Techniques, Evaluation]
---
We address the issue of hallucination in data-to-text generation, i.e.,
reducing the generation of text that is unsupported by the source. We
conjecture that hallucination can be caused by an encoder-decoder model
generating content phrases without attending to the source; so we propose a
confidence score to ensure that the model attends to the source whenever
necessary, as well as a variational Bayes training framework that can learn the
score from data. Experiments on the WikiBio (Lebretet al., 2016) dataset show
that our approach is more faithful to the source than existing state-of-the-art
approaches, according to both PARENT score (Dhingra et al., 2019) and human
evaluation. We also report strong results on the WebNLG (Gardent et al., 2017)
dataset.