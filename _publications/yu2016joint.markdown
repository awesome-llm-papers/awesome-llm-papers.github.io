---
layout: publication
title: A Joint Speaker-listener-reinforcer Model For Referring Expressions
authors: Licheng Yu, Hao Tan, Mohit Bansal, Tamara L. Berg
conference: 2017 IEEE Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2017
bibkey: yu2016joint
citations: 288
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1612.09542'}]
tags: ["CVPR", "Reinforcement Learning"]
short_authors: Yu et al.
---
Referring expressions are natural language constructions used to identify
particular objects within a scene. In this paper, we propose a unified
framework for the tasks of referring expression comprehension and generation.
Our model is composed of three modules: speaker, listener, and reinforcer. The
speaker generates referring expressions, the listener comprehends referring
expressions, and the reinforcer introduces a reward function to guide sampling
of more discriminative expressions. The listener-speaker modules are trained
jointly in an end-to-end learning framework, allowing the modules to be aware
of one another during learning while also benefiting from the discriminative
reinforcer's feedback. We demonstrate that this unified framework and training
achieves state-of-the-art results for both comprehension and generation on
three referring expression datasets. Project and demo page:
https://vision.cs.unc.edu/refer