---
layout: publication
title: A Syntactic Neural Model For General-purpose Code Generation
authors: Pengcheng Yin, Graham Neubig
conference: 'Proceedings of the 55th Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)'
year: 2017
bibkey: yin2017syntactic
citations: 543
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1704.01696'}]
tags: ["Llm For Code", "Model Architecture"]
short_authors: Pengcheng Yin, Graham Neubig
---
We consider the problem of parsing natural language descriptions into source
code written in a general-purpose programming language like Python. Existing
data-driven methods treat this problem as a language generation task without
considering the underlying syntax of the target programming language. Informed
by previous work in semantic parsing, in this paper we propose a novel neural
architecture powered by a grammar model to explicitly capture the target syntax
as prior knowledge. Experiments find this an effective way to scale up to
generation of complex programs from natural language descriptions, achieving
state-of-the-art results that well outperform previous code generation and
semantic parsing approaches.