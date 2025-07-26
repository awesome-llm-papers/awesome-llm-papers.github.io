---
layout: publication
title: Zero-shot Visual Question Answering
authors: Damien Teney, Anton van Den Hengel
conference: Arxiv
year: 2016
bibkey: teney2016zero
citations: 67
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1611.05546'}]
tags: ["Datasets", "Evaluation", "Training Techniques"]
short_authors: Damien Teney, Anton van Den Hengel
---
Part of the appeal of Visual Question Answering (VQA) is its promise to
answer new questions about previously unseen images. Most current methods
demand training questions that illustrate every possible concept, and will
therefore never achieve this capability, since the volume of required training
data would be prohibitive. Answering general questions about images requires
methods capable of Zero-Shot VQA, that is, methods able to answer questions
beyond the scope of the training questions. We propose a new evaluation
protocol for VQA methods which measures their ability to perform Zero-Shot VQA,
and in doing so highlights significant practical deficiencies of current
approaches, some of which are masked by the biases in current datasets. We
propose and evaluate several strategies for achieving Zero-Shot VQA, including
methods based on pretrained word embeddings, object classifiers with semantic
embeddings, and test-time retrieval of example images. Our extensive
experiments are intended to serve as baselines for Zero-Shot VQA, and they also
achieve state-of-the-art performance in the standard VQA evaluation setting.