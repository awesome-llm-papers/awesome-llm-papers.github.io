---
layout: publication
title: 'MOAT: Evaluating Lmms For Capability Integration And Instruction Grounding'
authors: Ye et al.
conference: IEEE Transactions on Circuits and Systems for Video Technology
year: 2025
bibkey: ye2025moat
citations: 54
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2503.09348'}]
tags: [Evaluation, Reinforcement Learning, Applications, Multimodal Models, Datasets]
---
Large multimodal models (LMMs) have demonstrated significant potential as
generalists in vision-language (VL) tasks. However, there remains a significant
gap between state-of-the-art LMMs and human performance when it comes to
complex tasks that require a combination of fundamental VL capabilities, as
well as tasks involving the grounding of complex instructions. To thoroughly
investigate the human-LMM gap and its underlying causes, we propose MOAT, a
diverse benchmark with complex real-world VL tasks that are challenging for
LMMs. Specifically, the tasks in MOAT require LMMs to engage in generalist
problem solving by integrating fundamental VL capabilities such as reading
text, counting, understanding spatial relations, grounding textual and visual
instructions, etc. All these abilities fit into a taxonomy proposed by us that
contains 10 fundamental VL capabilities, enabling MOAT to provide a
fine-grained view of LMMs' strengths and weaknesses. Besides, MOAT is the first
benchmark to explicitly evaluate LMMs' ability to ground complex text and
visual instructions, which is essential to many real-world applications. We
evaluate over 20 proprietary and open source LMMs, as well as humans, on MOAT,
and found that humans achieved 82.7% accuracy while the best performing LMM
(OpenAI o1) achieved only 38.8%. To guide future model development, we analyze
common trends in our results and discuss the underlying causes of observed
performance gaps between LMMs and humans, focusing on which VL capability forms
the bottleneck in complex tasks, whether test time scaling improves performance
on MOAT, and how tiling harms LMMs' capability to count. Code and data are
available at https://cambrian-yzt.github.io/MOAT.