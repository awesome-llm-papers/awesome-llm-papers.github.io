---
layout: publication
title: Program Of Equations Thoughts To Solve Algebra Word Problems
authors: Lin Yunze
conference: 'Proceedings of the 52nd Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)'
year: 2025
bibkey: lin2025program
citations: 116
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2505.20170'}]
tags: [Datasets, ACL]
---
Solving algebraic word problems (AWPs) has recently emerged as an important natural language processing task. Recently, large language models (LLMs) have demonstrated powerful mathematical capabilities, and the Chain-of-Thought technique, which guides LLMs through step-by-step reasoning, has yielded impressive results. However, this reasoning ability is limited by the computational weaknesses of LLMs themselves, where calculation errors can accumulate, leading to incorrect final answers. To address this, we propose Program of Equations Thoughts (POET), which transforms the task of generating step-by-step reasoning answers into a two-stage task of predicting equations and generating code, offloading complex computations to a Python interpreter to avoid calculation errors in LLMs. Furthermore, we propose Zero-shot POET, which utilizes a manually designed template to enable LLMs to directly generate Python code for one-step solving. Our method achieves accuracies of 95.3% and 98.0% on the PEN and ALG514 datasets, respectively, setting a new state-of-the-art (SOTA). Zero-shot POET also achieves the SOTA result of 95.5% on the DRAW-1K dataset.