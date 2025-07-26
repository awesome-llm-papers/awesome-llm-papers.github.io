---
layout: publication
title: Explainable Neural Computation Via Stack Neural Module Networks
authors: Ronghang Hu, Jacob Andreas, Trevor Darrell, Kate Saenko
conference: Lecture Notes in Computer Science
year: 2018
bibkey: hu2018explainable
citations: 189
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1807.08556'}]
tags: ["Applications", "Training Techniques"]
short_authors: Hu et al.
---
In complex inferential tasks like question answering, machine learning models
must confront two challenges: the need to implement a compositional reasoning
process, and, in many applications, the need for this reasoning process to be
interpretable to assist users in both development and prediction. Existing
models designed to produce interpretable traces of their decision-making
process typically require these traces to be supervised at training time. In
this paper, we present a novel neural modular approach that performs
compositional reasoning by automatically inducing a desired sub-task
decomposition without relying on strong supervision. Our model allows linking
different reasoning tasks though shared modules that handle common routines
across tasks. Experiments show that the model is more interpretable to human
evaluators compared to other state-of-the-art models: users can better
understand the model's underlying reasoning procedure and predict when it will
succeed or fail based on observing its intermediate outputs.