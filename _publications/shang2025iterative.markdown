---
layout: publication
title: Iterative Prompt Relocation For Distribution-adaptive Visual Prompt Tuning
authors: Shang et al.
conference: Lecture Notes in Computer Science
year: 2025
bibkey: shang2025iterative
citations: 796
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2503.06901'}]
tags: [RAG, Prompting, Tools, Evaluation, Efficiency And Optimization, Reinforcement
    Learning, Pruning, Datasets]
---
Visual prompt tuning (VPT) provides an efficient and effective solution for
adapting pre-trained models to various downstream tasks by incorporating
learnable prompts. However, most prior art indiscriminately applies a fixed
prompt distribution across different tasks, neglecting the importance of each
block differing depending on the task. In this paper, we investigate adaptive
distribution optimization (ADO) by addressing two key questions: (1) How to
appropriately and formally define ADO, and (2) How to design an adaptive
distribution strategy guided by this definition? Through in-depth analysis, we
provide an affirmative answer that properly adjusting the distribution
significantly improves VPT performance, and further uncover a key insight that
a nested relationship exists between ADO and VPT. Based on these findings, we
propose a new VPT framework, termed PRO-VPT (iterative Prompt RelOcation-based
VPT), which adaptively adjusts the distribution building upon a nested
optimization formulation. Specifically, we develop a prompt relocation strategy
for ADO derived from this formulation, comprising two optimization steps:
identifying and pruning idle prompts, followed by determining the optimal
blocks for their relocation. By iteratively performing prompt relocation and
VPT, our proposal adaptively learns the optimal prompt distribution, thereby
unlocking the full potential of VPT. Extensive experiments demonstrate that our
proposal significantly outperforms state-of-the-art VPT methods, e.g., PRO-VPT
surpasses VPT by 1.6% average accuracy, leading prompt-based methods to
state-of-the-art performance on the VTAB-1k benchmark. The code is available at
https://github.com/ckshang/PRO-VPT.