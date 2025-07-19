---
layout: publication
title: 'Relay: A High-level Compiler For Deep Learning'
authors: Roesch et al.
conference: Proceedings of the 27th ACM SIGSOFT International Symposium on Software
  Testing and Analysis
year: 2019
bibkey: roesch2019relay
citations: 103
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1904.08368'}]
tags: [Tools, Evaluation, Efficiency And Optimization, Reinforcement Learning, Merging]
---
Frameworks for writing, compiling, and optimizing deep learning (DL) models
have recently enabled progress in areas like computer vision and natural
language processing. Extending these frameworks to accommodate the rapidly
diversifying landscape of DL models and hardware platforms presents challenging
tradeoffs between expressivity, composability, and portability. We present
Relay, a new compiler framework for DL. Relay's functional, statically typed
intermediate representation (IR) unifies and generalizes existing DL IRs to
express state-of-the-art models. The introduction of Relay's expressive IR
requires careful design of domain-specific optimizations, addressed via Relay's
extension mechanisms. Using these extension mechanisms, Relay supports a
unified compiler that can target a variety of hardware platforms. Our
evaluation demonstrates Relay's competitive performance for a broad class of
models and devices (CPUs, GPUs, and emerging accelerators). Relay's design
demonstrates how a unified IR can provide expressivity, composability, and
portability without compromising performance.