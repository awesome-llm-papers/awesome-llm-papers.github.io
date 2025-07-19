---
layout: publication
title: Interpretable Visual Question Answering By Reasoning On Dependency Trees
authors: Cao et al.
conference: IEEE Transactions on Pattern Analysis and Machine Intelligence
year: 2018
bibkey: cao2018interpretable
citations: 51
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1809.01810'}]
tags: [Model Architecture, LLM for Code, Datasets, Attention Mechanism, Alt]
---
Collaborative reasoning for understanding image-question pairs is a very
critical but underexplored topic in interpretable visual question answering
systems. Although very recent studies have attempted to use explicit
compositional processes to assemble multiple subtasks embedded in questions,
their models heavily rely on annotations or handcrafted rules to obtain valid
reasoning processes, which leads to either heavy workloads or poor performance
on compositional reasoning. In this paper, to better align image and language
domains in diverse and unrestricted cases, we propose a novel neural network
model that performs global reasoning on a dependency tree parsed from the
question; thus, our model is called a parse-tree-guided reasoning network
(PTGRN). This network consists of three collaborative modules: i) an attention
module that exploits the local visual evidence of each word parsed from the
question, ii) a gated residual composition module that composes the previously
mined evidence, and iii) a parse-tree-guided propagation module that passes the
mined evidence along the parse tree. Thus, PTGRN is capable of building an
interpretable visual question answering (VQA) system that gradually derives
image cues following question-driven parse-tree reasoning. Experiments on
relational datasets demonstrate the superiority of PTGRN over current
state-of-the-art VQA methods, and the visualization results highlight the
explainable capability of our reasoning system.