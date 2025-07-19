---
layout: publication
title: 'Mcqa-eval: Efficient Confidence Evaluation In NLG With Gold-standard Correctness
  Labels'
authors: Liu et al.
conference: Proceedings of the 2023 Conference on Empirical Methods in Natural Language
  Processing
year: 2025
bibkey: liu2025mcqa
citations: 216
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2502.14268'}]
tags: [RAG, EMNLP, Alt, Tools, Evaluation, Ethics And Bias, Reinforcement Learning,
  Datasets]
---
Large Language Models (LLMs) require robust confidence estimation,
particularly in critical domains like healthcare and law where unreliable
outputs can lead to significant consequences. Despite much recent work in
confidence estimation, current evaluation frameworks rely on correctness
functions -- various heuristics that are often noisy, expensive, and possibly
introduce systematic biases. These methodological weaknesses tend to distort
evaluation metrics and thus the comparative ranking of confidence measures. We
introduce MCQA-Eval, an evaluation framework for assessing confidence measures
in Natural Language Generation (NLG) that eliminates dependence on an explicit
correctness function by leveraging gold-standard correctness labels from
multiple-choice datasets. MCQA-Eval enables systematic comparison of both
internal state-based white-box (e.g. logit-based) and consistency-based
black-box confidence measures, providing a unified evaluation methodology
across different approaches. Through extensive experiments on multiple LLMs and
widely used QA datasets, we report that MCQA-Eval provides efficient and more
reliable assessments of confidence estimation methods than existing approaches.