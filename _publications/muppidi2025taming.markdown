---
layout: publication
title: 'Taming Llms With Negative Samples: A Reference-free Framework To Evaluate
  Presentation Content With Actionable Feedback'
authors: Muppidi et al.
conference: IEEE Transactions on Knowledge and Data Engineering
year: 2025
bibkey: muppidi2025taming
citations: 93
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2505.18240'}]
tags: [Interpretability And Explainability, Tools, Evaluation, Multimodal Models,
  Datasets]
---
The generation of presentation slides automatically is an important problem in the era of generative AI. This paper focuses on evaluating multimodal content in presentation slides that can effectively summarize a document and convey concepts to a broad audience. We introduce a benchmark dataset, RefSlides, consisting of human-made high-quality presentations that span various topics. Next, we propose a set of metrics to characterize different intrinsic properties of the content of a presentation and present REFLEX, an evaluation approach that generates scores and actionable feedback for these metrics. We achieve this by generating negative presentation samples with different degrees of metric-specific perturbations and use them to fine-tune LLMs. This reference-free evaluation technique does not require ground truth presentations during inference. Our extensive automated and human experiments demonstrate that our evaluation approach outperforms classical heuristic-based and state-of-the-art large language model-based evaluations in generating scores and explanations.