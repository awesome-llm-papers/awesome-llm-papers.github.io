---
layout: publication
title: 'Dualprompt: Complementary Prompting For Rehearsal-free Continual Learning'
authors: Zifeng Wang et al.
conference: Lecture Notes in Computer Science
year: 2022
citations: 182
bibkey: wang2022complementary
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2204.04799'}, {name: Code,
    url: 'https://github.com/google-research/l2p'}]
tags: [Has Code, Tools, Reinforcement Learning, Prompting, Evaluation]
---
Continual learning aims to enable a single model to learn a sequence of tasks
without catastrophic forgetting. Top-performing methods usually require a
rehearsal buffer to store past pristine examples for experience replay, which,
however, limits their practical value due to privacy and memory constraints. In
this work, we present a simple yet effective framework, DualPrompt, which
learns a tiny set of parameters, called prompts, to properly instruct a
pre-trained model to learn tasks arriving sequentially without buffering past
examples. DualPrompt presents a novel approach to attach complementary prompts
to the pre-trained backbone, and then formulates the objective as learning
task-invariant and task-specific "instructions". With extensive experimental
validation, DualPrompt consistently sets state-of-the-art performance under the
challenging class-incremental setting. In particular, DualPrompt outperforms
recent advanced continual learning methods with relatively large buffer sizes.
We also introduce a more challenging benchmark, Split ImageNet-R, to help
generalize rehearsal-free continual learning research. Source code is available
at https://github.com/google-research/l2p.