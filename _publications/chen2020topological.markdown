---
layout: publication
title: Topological Planning With Transformers For Vision-and-language Navigation
authors: Chen et al.
conference: 2021 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2020
bibkey: chen2020topological
citations: 62
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2012.05292'}]
tags: [RAG, Attention Mechanism, CVPR, Transformer, Model Architecture]
---
Conventional approaches to vision-and-language navigation (VLN) are trained
end-to-end but struggle to perform well in freely traversable environments.
Inspired by the robotics community, we propose a modular approach to VLN using
topological maps. Given a natural language instruction and topological map, our
approach leverages attention mechanisms to predict a navigation plan in the
map. The plan is then executed with low-level actions (e.g. forward, rotate)
using a robust controller. Experiments show that our method outperforms
previous end-to-end approaches, generates interpretable navigation plans, and
exhibits intelligent behaviors such as backtracking.