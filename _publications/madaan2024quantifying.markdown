---
layout: publication
title: Quantifying Variance In Evaluation Benchmarks
authors: Madaan et al.
conference: Monthly Notices of the Royal Astronomical Society
year: 2024
bibkey: madaan2024quantifying
citations: 156
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2406.10229'}]
tags: [Datasets, RAG, Evaluation, Training Techniques]
---
Evaluation benchmarks are the cornerstone of measuring capabilities of large
language models (LLMs), as well as driving progress in said capabilities.
Originally designed to make claims about capabilities (or lack thereof) in
fully pretrained models, evaluation benchmarks are now also extensively used to
decide between various training choices. Despite this widespread usage, we
rarely quantify the variance in our evaluation benchmarks, which dictates
whether differences in performance are meaningful. Here, we define and measure
a range of metrics geared towards measuring variance in evaluation benchmarks,
including seed variance across initialisations, and monotonicity during
training. By studying a large number of models -- both openly available and
pretrained from scratch -- we provide empirical estimates for a variety of
variance metrics, with considerations and recommendations for practitioners. We
also evaluate the utility and tradeoffs of continuous versus discrete
performance measures and explore options for better understanding and reducing
this variance. We find that simple changes, such as framing choice tasks (like
MMLU) as completion tasks, can often reduce variance for smaller scale
(\\(\sim\\)7B) models, while more involved methods inspired from human testing
literature (such as item analysis and item response theory) struggle to
meaningfully reduce variance. Overall, our work provides insights into variance
in evaluation benchmarks, suggests LM-specific techniques to reduce variance,
and more generally encourages practitioners to carefully factor in variance
when comparing models.