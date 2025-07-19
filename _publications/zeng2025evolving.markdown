---
layout: publication
title: Evolving Llms' Self-refinement Capability Via Iterative Preference Optimization
authors: Zeng et al.
conference: 2022 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2025
bibkey: zeng2025evolving
citations: 51
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2502.05605'}]
tags: [RAG, Training Techniques, GPT, Tools, CVPR, Model Architecture, Efficiency
    And Optimization, Datasets]
---
While large language models (LLMs) have demonstrated remarkable general performance, enabling smaller models to achieve capabilities comparable to their larger counterparts remains a critical challenge. For humans, iterative refinement of problem analysis and responses is a common strategy to enhance answer quality. However, we observe that existing LLMs exhibit limited ability to refine their outputs for quality improvement. In this paper, we first investigate mechanisms to unlock and progressively enhance self-refinement ability in smaller models within an iterative preference optimization framework, aiming to bridge the performance gap with larger models. To this end, we propose EVOLVE, a novel post-training and inference framework that iteratively integrates preference training with self-refinement-driven data collection. During training, EVOLVE strengthens the model's direct question-answering ability while simultaneously unlocking its self-refinement potential. At inference, the framework leverages this capability to generate progressively refined responses, which are filtered to construct datasets for subsequent rounds of preference training. Experiments demonstrate EVOLVE's exceptional performance: when applied to Llama-3.1-8B base model and under the self-refinement setting, it surpasses state-of-the-art models including Llama-3.1-405B-Instruct and GPT-4o, achieving a 62.3% length-controlled win rate and 63.3% raw win rate on AlpacaEval 2, along with a 50.3% win rate on Arena-Hard. Furthermore, EVOLVE consistently enhances performance on mathematical reasoning tasks like GSM8K and MATH.