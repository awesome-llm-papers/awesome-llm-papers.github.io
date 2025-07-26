---
layout: publication
title: 'IQA: Visual Question Answering In Interactive Environments'
authors: Daniel Gordon, Aniruddha Kembhavi, Mohammad Rastegari, Joseph Redmon, Dieter
  Fox, Ali Farhadi
conference: 2018 IEEE/CVF Conference on Computer Vision and Pattern Recognition
year: 2018
bibkey: gordon2017iqa
citations: 348
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1712.03316'}]
tags: ["CVPR"]
short_authors: Gordon et al.
---
We introduce Interactive Question Answering (IQA), the task of answering
questions that require an autonomous agent to interact with a dynamic visual
environment. IQA presents the agent with a scene and a question, like: "Are
there any apples in the fridge?" The agent must navigate around the scene,
acquire visual understanding of scene elements, interact with objects (e.g.
open refrigerators) and plan for a series of actions conditioned on the
question. Popular reinforcement learning approaches with a single controller
perform poorly on IQA owing to the large and diverse state space. We propose
the Hierarchical Interactive Memory Network (HIMN), consisting of a factorized
set of controllers, allowing the system to operate at multiple levels of
temporal abstraction. To evaluate HIMN, we introduce IQUAD V1, a new dataset
built upon AI2-THOR, a simulated photo-realistic environment of configurable
indoor scenes with interactive objects (code and dataset available at
https://github.com/danielgordon10/thor-iqa-cvpr-2018). IQUAD V1 has 75,000
questions, each paired with a unique scene configuration. Our experiments show
that our proposed model outperforms popular single controller based methods on
IQUAD V1. For sample questions and results, please view our video:
https://youtu.be/pXd3C-1jr98