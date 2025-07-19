---
layout: publication
title: Instruction Distillation Makes Large Language Models Efficient Zero-shot Rankers
authors: Sun et al.
conference: Lecture Notes in Computer Science
year: 2023
bibkey: sun2023instruction
citations: 118
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2311.01555'}]
tags: [Distillation, GPT, Alt, Prompting, Evaluation, Model Architecture, Efficiency
    And Optimization, Datasets]
---
Recent studies have demonstrated the great potential of Large Language Models
(LLMs) serving as zero-shot relevance rankers. The typical approach involves
making comparisons between pairs or lists of documents. Although effective,
these listwise and pairwise methods are not efficient and also heavily rely on
intricate prompt engineering. To tackle this problem, we introduce a novel
instruction distillation method. The key idea is to distill the pairwise
ranking ability of open-sourced LLMs to a simpler but more efficient pointwise
ranking. Specifically, given the same LLM, we first rank documents using the
effective pairwise approach with complex instructions, and then distill the
teacher predictions to the pointwise approach with simpler instructions.
Evaluation results on the BEIR, TREC, and ReDial datasets demonstrate that
instruction distillation can improve efficiency by 10 to 100x and also enhance
the ranking performance of LLMs. Furthermore, our approach surpasses the
performance of existing supervised methods like monoT5 and is on par with the
state-of-the-art zero-shot methods. The code to reproduce our results is
available at www.github.com/sunnweiwei/RankGPT.