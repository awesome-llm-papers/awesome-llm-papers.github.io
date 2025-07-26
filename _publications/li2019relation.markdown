---
layout: publication
title: Relation-aware Graph Attention Network For Visual Question Answering
authors: Linjie Li, Zhe Gan, Yu Cheng, Jingjing Liu
conference: 2019 IEEE/CVF International Conference on Computer Vision (ICCV)
year: 2019
bibkey: li2019relation
citations: 357
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1903.12314'}]
tags: ["ICCV", "Model Architecture"]
short_authors: Li et al.
---
In order to answer semantically-complicated questions about an image, a
Visual Question Answering (VQA) model needs to fully understand the visual
scene in the image, especially the interactive dynamics between different
objects. We propose a Relation-aware Graph Attention Network (ReGAT), which
encodes each image into a graph and models multi-type inter-object relations
via a graph attention mechanism, to learn question-adaptive relation
representations. Two types of visual object relations are explored: (i)
Explicit Relations that represent geometric positions and semantic interactions
between objects; and (ii) Implicit Relations that capture the hidden dynamics
between image regions. Experiments demonstrate that ReGAT outperforms prior
state-of-the-art approaches on both VQA 2.0 and VQA-CP v2 datasets. We further
show that ReGAT is compatible to existing VQA architectures, and can be used as
a generic relation encoder to boost the model performance for VQA.