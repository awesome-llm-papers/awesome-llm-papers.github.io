---
layout: publication
title: Scene Text Recognition With Permuted Autoregressive Sequence Models
authors: Darwin Bautista, Rowel Atienza
conference: Lecture Notes in Computer Science
year: 2022
bibkey: bautista2022scene
citations: 137
additional_links: [{name: Code, url: 'https://github.com/baudm/parseq'}, {name: Paper,
    url: 'https://arxiv.org/abs/2207.06966'}]
tags: ["Datasets", "Has Code", "Training Techniques"]
short_authors: Darwin Bautista, Rowel Atienza
---
Context-aware STR methods typically use internal autoregressive (AR) language
models (LM). Inherent limitations of AR models motivated two-stage methods
which employ an external LM. The conditional independence of the external LM on
the input image may cause it to erroneously rectify correct predictions,
leading to significant inefficiencies. Our method, PARSeq, learns an ensemble
of internal AR LMs with shared weights using Permutation Language Modeling. It
unifies context-free non-AR and context-aware AR inference, and iterative
refinement using bidirectional context. Using synthetic training data, PARSeq
achieves state-of-the-art (SOTA) results in STR benchmarks (91.9% accuracy) and
more challenging datasets. It establishes new SOTA results (96.0% accuracy)
when trained on real data. PARSeq is optimal on accuracy vs parameter count,
FLOPS, and latency because of its simple, unified structure and parallel token
processing. Due to its extensive use of attention, it is robust on
arbitrarily-oriented text which is common in real-world images. Code,
pretrained weights, and data are available at: https://github.com/baudm/parseq.