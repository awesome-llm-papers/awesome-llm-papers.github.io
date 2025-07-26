---
layout: publication
title: Inferring And Executing Programs For Visual Reasoning
authors: Justin Johnson, Bharath Hariharan, Laurens van Der Maaten, Judy Hoffman,
  Li Fei-fei, C. Lawrence Zitnick, Ross Girshick
conference: 2017 IEEE International Conference on Computer Vision (ICCV)
year: 2017
bibkey: johnson2017inferring
citations: 529
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1705.03633'}]
tags: ["ICCV"]
short_authors: Johnson et al.
---
Existing methods for visual reasoning attempt to directly map inputs to
outputs using black-box architectures without explicitly modeling the
underlying reasoning processes. As a result, these black-box models often learn
to exploit biases in the data rather than learning to perform visual reasoning.
Inspired by module networks, this paper proposes a model for visual reasoning
that consists of a program generator that constructs an explicit representation
of the reasoning process to be performed, and an execution engine that executes
the resulting program to produce an answer. Both the program generator and the
execution engine are implemented by neural networks, and are trained using a
combination of backpropagation and REINFORCE. Using the CLEVR benchmark for
visual reasoning, we show that our model significantly outperforms strong
baselines and generalizes better in a variety of settings.