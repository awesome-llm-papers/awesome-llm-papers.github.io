---
layout: publication
title: 'Maieutic Prompting: Logically Consistent Reasoning With Recursive Explanations'
authors: Jung et al.
conference: Proceedings of the 2022 Conference on Empirical Methods in Natural Language
  Processing
year: 2022
bibkey: jung2022maieutic
citations: 56
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2205.11822'}]
tags: [Interpretability And Explainability, EMNLP, Prompting, Evaluation, Security,
  Datasets]
---
Despite their impressive capabilities, large pre-trained language models
(LMs) struggle with consistent reasoning; recently, prompting LMs to generate
explanations that self-guide the inference has emerged as a promising direction
to amend this. However, these approaches are fundamentally bounded by the
correctness of explanations, which themselves are often noisy and inconsistent.
In this work, we develop Maieutic Prompting, which infers a correct answer to a
question even from the noisy and inconsistent generations of LM. Maieutic
Prompting induces a tree of explanations abductively (e.g. X is true, because
...) and recursively, then frames the inference as a satisfiability problem
over these explanations and their logical relations. We test Maieutic Prompting
for true/false QA on three challenging benchmarks that require complex
commonsense reasoning. Maieutic Prompting achieves up to 20% better accuracy
than state-of-the-art prompting methods, and as a fully unsupervised approach,
performs competitively with supervised models. We also show that Maieutic
Prompting improves robustness in inference while providing interpretable
rationales.