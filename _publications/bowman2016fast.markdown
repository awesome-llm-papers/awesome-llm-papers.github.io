---
layout: publication
title: A Fast Unified Model For Parsing And Sentence Understanding
authors: Samuel R. Bowman, Jon Gauthier, Abhinav Rastogi, Raghav Gupta, Christopher
  D. Manning, Christopher Potts
conference: 'Proceedings of the 54th Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)'
year: 2016
bibkey: bowman2016fast
citations: 246
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1603.06021'}]
tags: ["Efficiency", "Model Architecture"]
short_authors: Bowman et al.
---
Tree-structured neural networks exploit valuable syntactic parse information
as they interpret the meanings of sentences. However, they suffer from two key
technical problems that make them slow and unwieldy for large-scale NLP tasks:
they usually operate on parsed sentences and they do not directly support
batched computation. We address these issues by introducing the Stack-augmented
Parser-Interpreter Neural Network (SPINN), which combines parsing and
interpretation within a single tree-sequence hybrid model by integrating
tree-structured sentence interpretation into the linear sequential structure of
a shift-reduce parser. Our model supports batched computation for a speedup of
up to 25 times over other tree-structured models, and its integrated parser can
operate on unparsed data with little loss in accuracy. We evaluate it on the
Stanford NLI entailment task and show that it significantly outperforms other
sentence-encoding models.