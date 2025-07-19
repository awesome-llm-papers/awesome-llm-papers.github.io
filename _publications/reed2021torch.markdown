---
layout: publication
title: 'Torch.fx: Practical Program Capture And Transformation For Deep Learning In
  Python'
authors: Reed et al.
conference: Arxiv
year: 2021
bibkey: reed2021torch
citations: 82
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2112.08429'}]
tags: [Efficiency And Optimization, Tools, Applications]
---
Modern deep learning frameworks provide imperative, eager execution
programming interfaces embedded in Python to provide a productive development
experience. However, deep learning practitioners sometimes need to capture and
transform program structure for performance optimization, visualization,
analysis, and hardware integration. We study the different designs for program
capture and transformation used in deep learning. By designing for typical deep
learning use cases rather than long tail ones, it is possible to create a
simpler framework for program capture and transformation. We apply this
principle in torch.fx, a program capture and transformation library for PyTorch
written entirely in Python and optimized for high developer productivity by ML
practitioners. We present case studies showing how torch.fx enables workflows
previously inaccessible in the PyTorch ecosystem.