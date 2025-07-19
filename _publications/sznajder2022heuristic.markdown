---
layout: publication
title: Heuristic-based Inter-training To Improve Few-shot Multi-perspective Dialog
  Summarization
authors: Sznajder et al.
conference: Proceedings of the 37th IEEE/ACM International Conference on Automated
  Software Engineering
year: 2022
bibkey: sznajder2022heuristic
citations: 139
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2203.15590'}]
tags: [Fine Tuning, Training Techniques, LLM For Code, Agentic, Few Shot, LLM for
    Code, Reinforcement Learning]
---
Many organizations require their customer-care agents to manually summarize
their conversations with customers. These summaries are vital for decision
making purposes of the organizations. The perspective of the summary that is
required to be created depends on the application of the summaries. With this
work, we study the multi-perspective summarization of customer-care
conversations between support agents and customers. We observe that there are
different heuristics that are associated with summaries of different
perspectives, and explore these heuristics to create weak-labeled data for
intermediate training of the models before fine-tuning with scarce human
annotated summaries. Most importantly, we show that our approach supports
models to generate multi-perspective summaries with a very small amount of
annotated data. For example, our approach achieves 94% of the performance
(Rouge-2) of a model trained with the original data, by training only with 7%
of the original data.