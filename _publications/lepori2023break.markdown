---
layout: publication
title: 'Break It Down: Evidence For Structural Compositionality In Neural Networks'
authors: Lepori Michael A., Serre Thomas, Pavlick Ellie
conference: Journal of Artificial Intelligence Research
year: 2023
bibkey: lepori2023break
citations: 58
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2301.10884'}]
tags: [RAG, Training Techniques, Model Architecture, Efficiency And Optimization,
  Pruning]
---
Though modern neural networks have achieved impressive performance in both
vision and language tasks, we know little about the functions that they
implement. One possibility is that neural networks implicitly break down
complex tasks into subroutines, implement modular solutions to these
subroutines, and compose them into an overall solution to a task - a property
we term structural compositionality. Another possibility is that they may
simply learn to match new inputs to learned templates, eliding task
decomposition entirely. Here, we leverage model pruning techniques to
investigate this question in both vision and language across a variety of
architectures, tasks, and pretraining regimens. Our results demonstrate that
models often implement solutions to subroutines via modular subnetworks, which
can be ablated while maintaining the functionality of other subnetworks. This
suggests that neural networks may be able to learn compositionality, obviating
the need for specialized symbolic mechanisms.