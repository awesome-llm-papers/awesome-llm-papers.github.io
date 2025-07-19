---
layout: publication
title: Demystifying And Assessing Code Understandability In Java Decompilation
authors: Qin et al.
conference: IEEE Transactions on Software Engineering
year: 2024
bibkey: qin2024demystifying
citations: 57
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2409.20343'}]
tags: [Datasets, LLM for Code, LLM For Code, Evaluation]
---
Decompilation, the process of converting machine-level code into readable
source code, plays a critical role in reverse engineering. Given that the main
purpose of decompilation is to facilitate code comprehension in scenarios where
the source code is unavailable, the understandability of decompiled code is of
great importance. In this paper, we propose the first empirical study on the
understandability of Java decompiled code and obtained the following findings:
(1) Understandability of Java decompilation is considered as important as its
correctness, and decompilation understandability issues are even more commonly
encountered than decompilation failures. (2) A notable percentage of code
snippets decompiled by Java decompilers exhibit significantly lower or higher
levels of understandability in comparison to their original source code. (3)
Unfortunately, Cognitive Complexity demonstrates relatively acceptable
precision while low recall in recognizing these code snippets exhibiting
diverse understandability during decompilation. (4) Even worse, perplexity
demonstrates lower levels of precision and recall in recognizing such code
snippets. Inspired by the four findings, we further proposed six code patterns
and the first metric for the assessment of decompiled code understandability.
This metric was extended from Cognitive Complexity, with six more rules
harvested from an exhaustive manual analysis into 1287 pairs of source code
snippets and corresponding decompiled code. This metric was also validated
using the original and updated dataset, yielding an impressive macro F1-score
of 0.88 on the original dataset, and 0.86 on the test set.