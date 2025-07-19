---
layout: publication
title: Iterative Visual Reasoning Beyond Convolutions
authors: Chen et al.
conference: 2018 IEEE/CVF Conference on Computer Vision and Pattern Recognition
year: 2018
bibkey: chen2018iterative
citations: 234
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1803.11189'}]
tags: [RAG, Attention Mechanism, Tools, CVPR, Transformer, Model Architecture]
---
We present a novel framework for iterative visual reasoning. Our framework
goes beyond current recognition systems that lack the capability to reason
beyond stack of convolutions. The framework consists of two core modules: a
local module that uses spatial memory to store previous beliefs with parallel
updates; and a global graph-reasoning module. Our graph module has three
components: a) a knowledge graph where we represent classes as nodes and build
edges to encode different types of semantic relationships between them; b) a
region graph of the current image where regions in the image are nodes and
spatial relationships between these regions are edges; c) an assignment graph
that assigns regions to classes. Both the local module and the global module
roll-out iteratively and cross-feed predictions to each other to refine
estimates. The final predictions are made by combining the best of both modules
with an attention mechanism. We show strong performance over plain ConvNets,
\eg achieving an \\(8.4%\\) absolute improvement on ADE measured by per-class
average precision. Analysis also shows that the framework is resilient to
missing regions for reasoning.