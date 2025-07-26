---
layout: publication
title: Can This Model Also Recognize Dogs? Zero-shot Model Search From Weights
authors: Jonathan Kahana, Or Nathan, Eliahu Horwitz, Yedid Hoshen
conference: No Venue
year: 2025
bibkey: kahana2025can
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/67aef6222c36e4d8bd237472'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2502.09619'}]
tags: ["Training Techniques"]
short_authors: Kahana et al.
---
With the increasing numbers of publicly available models, there are probably pretrained, online models for most tasks users require. However, current model search methods are rudimentary, essentially a text-based search in the documentation, thus users cannot find the relevant models. This paper presents ProbeLog, a method for retrieving classification models that can recognize a target concept, such as "Dog", without access to model metadata or training data. Differently from previous probing methods, ProbeLog computes a descriptor for each output dimension (logit) of each model, by observing its responses on a fixed set of inputs (probes). Our method supports both logit-based retrieval ("find more logits like this") and zero-shot, text-based retrieval ("find all logits corresponding to dogs"). As probing-based representations require multiple costly feedforward passes through the model, we develop a method, based on collaborative filtering, that reduces the cost of encoding repositories by 3x. We demonstrate that ProbeLog achieves high retrieval accuracy, both in real-world and fine-grained search tasks and is scalable to full-size repositories.

https://huggingface.co/discussions/paper/67aef6222c36e4d8bd237472