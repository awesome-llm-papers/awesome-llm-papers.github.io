---
layout: publication
title: Transferable Representation Learning In Vision-and-language Navigation
authors: Haoshuo Huang, Vihan Jain, Harsh Mehta, Alexander Ku, Gabriel Magalhaes,
  Jason Baldridge, Eugene Ie
conference: 2019 IEEE/CVF International Conference on Computer Vision (ICCV)
year: 2019
bibkey: huang2019transferable
citations: 83
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1908.03409'}]
tags: ["ICCV"]
short_authors: Huang et al.
---
Vision-and-Language Navigation (VLN) tasks such as Room-to-Room (R2R) require
machine agents to interpret natural language instructions and learn to act in
visually realistic environments to achieve navigation goals. The overall task
requires competence in several perception problems: successful agents combine
spatio-temporal, vision and language understanding to produce appropriate
action sequences. Our approach adapts pre-trained vision and language
representations to relevant in-domain tasks making them more effective for VLN.
Specifically, the representations are adapted to solve both a cross-modal
sequence alignment and sequence coherence task. In the sequence alignment task,
the model determines whether an instruction corresponds to a sequence of visual
frames. In the sequence coherence task, the model determines whether the
perceptual sequences are predictive sequentially in the instruction-conditioned
latent space. By transferring the domain-adapted representations, we improve
competitive agents in R2R as measured by the success rate weighted by path
length (SPL) metric.