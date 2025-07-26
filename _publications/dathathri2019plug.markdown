---
layout: publication
title: 'Plug And Play Language Models: A Simple Approach To Controlled Text Generation'
authors: Sumanth Dathathri, Andrea Madotto, Janice Lan, Jane Hung, Eric Frank, Piero
  Molino, Jason Yosinski, Rosanne Liu
conference: Arxiv
year: 2019
bibkey: dathathri2019plug
citations: 439
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1912.02164'}]
tags: ["Applications", "Model Architecture"]
short_authors: Dathathri et al.
---
Large transformer-based language models (LMs) trained on huge text corpora
have shown unparalleled generation capabilities. However, controlling
attributes of the generated language (e.g. switching topic or sentiment) is
difficult without modifying the model architecture or fine-tuning on
attribute-specific data and entailing the significant cost of retraining. We
propose a simple alternative: the Plug and Play Language Model (PPLM) for
controllable language generation, which combines a pretrained LM with one or
more simple attribute classifiers that guide text generation without any
further training of the LM. In the canonical scenario we present, the attribute
models are simple classifiers consisting of a user-specified bag of words or a
single learned layer with 100,000 times fewer parameters than the LM. Sampling
entails a forward and backward pass in which gradients from the attribute model
push the LM's hidden activations and thus guide the generation. Model samples
demonstrate control over a range of topics and sentiment styles, and extensive
automated and human annotated evaluations show attribute alignment and fluency.
PPLMs are flexible in that any combination of differentiable attribute models
may be used to steer text generation, which will allow for diverse and creative
applications beyond the examples given in this paper.