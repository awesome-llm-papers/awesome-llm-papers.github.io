---
layout: publication
title: 'HALC: Object Hallucination Reduction Via Adaptive Focal-contrast Decoding'
authors: Chen et al.
conference: IEEE Transactions on Circuits and Systems for Video Technology
year: 2024
bibkey: chen2024halc
citations: 83
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2403.00425'}]
tags: [RAG, Training Techniques, Evaluation, Language Modeling, Multimodal Models,
  Datasets]
---
While large vision-language models (LVLMs) have demonstrated impressive
capabilities in interpreting multi-modal contexts, they invariably suffer from
object hallucinations (OH). We introduce HALC, a novel decoding algorithm
designed to mitigate OH in LVLMs. HALC leverages distinct fine-grained optimal
visual information in vision-language tasks and operates on both local and
global contexts simultaneously. Specifically, HALC integrates a robust
auto-focal grounding mechanism (locally) to correct hallucinated tokens on the
fly, and a specialized beam search algorithm (globally) to significantly reduce
OH while preserving text generation quality. Additionally, HALC can be
integrated into any LVLMs as a plug-and-play module without extra training.
Extensive experimental studies demonstrate the effectiveness of HALC in
reducing OH, outperforming state-of-the-arts across four benchmarks.