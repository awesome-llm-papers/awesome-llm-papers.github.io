---
layout: publication
title: 'Advancing Tool-augmented Large Language Models: Integrating Insights From
  Errors In Inference Trees'
authors: Chen et al.
conference: Medicina
year: 2024
bibkey: chen2024advancing
citations: 65
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2406.07115'}]
tags: [RAG, Training Techniques, Agentic, Tools, Efficiency And Optimization, Reinforcement
    Learning, Fine Tuning]
---
Tool-augmented large language models (LLMs) leverage tools, often in the form
of APIs, to improve their reasoning capabilities on complex tasks. This enables
them to act as intelligent agents interacting with the real world. The recently
introduced ToolLLaMA model by Qin et al. [2023] utilizes the depth-first
search-based decision tree (DFSDT) mechanism for multi-step reasoning with
\\(16000+\\) real-world APIs, effectively enhancing the performance of
tool-augmented LLMs compared to traditional chain reasoning mechanisms.
However, their approach only employs successful paths from decision trees (also
called inference trees) for supervised fine-tuning (SFT), missing out on the
potential learning opportunities from failed paths. Inspired by this, we
propose an inference trajectory optimization framework based on preference
learning to address this limitation. We first introduce a novel method for
constructing step-wise preference data from tree-like expert trajectories,
which leverages the previously ignored failed explorations in the decision
trees. In the subsequent training phase, we first fine-tune the LLM with
successful tool-usage expert trajectories and then apply direct preference
optimization (DPO) with the preference data to update the LLM's policy,
resulting in our ToolPrefer-LLaMA (TP-LLaMA) model. This approach not only
enhances the utilization of original expert data but also broadens the learning
space of the model. Our experiments demonstrate that by obtaining insights from
errors in inference trees, TP-LLaMA significantly outperforms the baselines
across almost all test scenarios by a large margin and exhibits better
generalization capabilities with unseen APIs. At the same time, TP-LLaMA has
also demonstrated superior reasoning efficiency compared to the baselines,
making it more suitable for complex tool-usage reasoning tasks.