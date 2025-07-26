---
layout: publication
title: 'Treegen: A Tree-based Transformer Architecture For Code Generation'
authors: Zeyu Sun, Qihao Zhu, Yingfei Xiong, Yican Sun, Lili Mou, Lu Zhang
conference: Proceedings of the AAAI Conference on Artificial Intelligence
year: 2020
bibkey: sun2019treegen
citations: 146
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1911.09983'}]
tags: ["AAAI", "Llm For Code", "Model Architecture"]
short_authors: Sun et al.
---
A code generation system generates programming language code based on an
input natural language description. State-of-the-art approaches rely on neural
networks for code generation. However, these code generators suffer from two
problems. One is the long dependency problem, where a code element often
depends on another far-away code element. A variable reference, for example,
depends on its definition, which may appear quite a few lines before. The other
problem is structure modeling, as programs contain rich structural information.
In this paper, we propose a novel tree-based neural architecture, TreeGen, for
code generation. TreeGen uses the attention mechanism of Transformers to
alleviate the long-dependency problem, and introduces a novel AST reader
(encoder) to incorporate grammar rules and AST structures into the network. We
evaluated TreeGen on a Python benchmark, HearthStone, and two semantic parsing
benchmarks, ATIS and GEO. TreeGen outperformed the previous state-of-the-art
approach by 4.5 percentage points on HearthStone, and achieved the best
accuracy among neural network-based approaches on ATIS (89.1%) and GEO (89.6%).
We also conducted an ablation test to better understand each component of our
model.