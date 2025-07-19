---
layout: publication
title: Use Hirescam Instead Of Grad-cam For Faithful Explanations Of Convolutional
  Neural Networks
authors: Draelos Rachel Lea, Carin Lawrence
conference: Arxiv
year: 2020
bibkey: draelos2020use
citations: 64
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2011.08891'}]
tags: [Interpretability And Explainability, RAG, Attention Mechanism, Evaluation,
  Model Architecture, Applications]
---
Explanation methods facilitate the development of models that learn
meaningful concepts and avoid exploiting spurious correlations. We illustrate a
previously unrecognized limitation of the popular neural network explanation
method Grad-CAM: as a side effect of the gradient averaging step, Grad-CAM
sometimes highlights locations the model did not actually use. To solve this
problem, we propose HiResCAM, a novel class-specific explanation method that is
guaranteed to highlight only the locations the model used to make each
prediction. We prove that HiResCAM is a generalization of CAM and explore the
relationships between HiResCAM and other gradient-based explanation methods.
Experiments on PASCAL VOC 2012, including crowd-sourced evaluations, illustrate
that while HiResCAM's explanations faithfully reflect the model, Grad-CAM often
expands the attention to create bigger and smoother visualizations. Overall,
this work advances convolutional neural network explanation approaches and may
aid in the development of trustworthy models for sensitive applications.