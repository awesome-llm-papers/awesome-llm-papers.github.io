---
layout: publication
title: Faithful Explanations Of Black-box NLP Models Using Llm-generated Counterfactuals
authors: Gat et al.
conference: Proceedings of the 2019 AAAI/ACM Conference on AI, Ethics, and Society
year: 2023
bibkey: gat2023faithful
citations: 147
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2310.00603'}]
tags: [Interpretability And Explainability, Datasets, Training Techniques, Prompting,
  Evaluation, Ethics And Bias, AAAI, Responsible AI]
---
Causal explanations of the predictions of NLP systems are essential to ensure
safety and establish trust. Yet, existing methods often fall short of
explaining model predictions effectively or efficiently and are often
model-specific. In this paper, we address model-agnostic explanations,
proposing two approaches for counterfactual (CF) approximation. The first
approach is CF generation, where a large language model (LLM) is prompted to
change a specific text concept while keeping confounding concepts unchanged.
While this approach is demonstrated to be very effective, applying LLM at
inference-time is costly. We hence present a second approach based on matching,
and propose a method that is guided by an LLM at training-time and learns a
dedicated embedding space. This space is faithful to a given causal graph and
effectively serves to identify matches that approximate CFs. After showing
theoretically that approximating CFs is required in order to construct faithful
explanations, we benchmark our approaches and explain several models, including
LLMs with billions of parameters. Our empirical results demonstrate the
excellent performance of CF generation models as model-agnostic explainers.
Moreover, our matching approach, which requires far less test-time resources,
also provides effective explanations, surpassing many baselines. We also find
that Top-K techniques universally improve every tested method. Finally, we
showcase the potential of LLMs in constructing new benchmarks for model
explanation and subsequently validate our conclusions. Our work illuminates new
pathways for efficient and accurate approaches to interpreting NLP systems.