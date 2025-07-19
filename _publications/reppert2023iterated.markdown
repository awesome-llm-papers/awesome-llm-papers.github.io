---
layout: publication
title: 'Iterated Decomposition: Improving Science Q&A By Supervising Reasoning Processes'
authors: Reppert et al.
conference: IEEE Transactions on Software Engineering
year: 2023
bibkey: reppert2023iterated
citations: 87
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2301.01751'}]
tags: [Interpretability And Explainability, LLM For Code, Applications, LLM for Code,
  Datasets, Reinforcement Learning, Responsible AI]
---
Language models (LMs) can perform complex reasoning either end-to-end, with
hidden latent state, or compositionally, with transparent intermediate state.
Composition offers benefits for interpretability and safety, but may need
workflow support and infrastructure to remain competitive. We describe iterated
decomposition, a human-in-the-loop workflow for developing and refining
compositional LM programs. We improve the performance of compositions by
zooming in on failing components and refining them through decomposition,
additional context, chain of thought, etc. To support this workflow, we develop
ICE, an open-source tool for visualizing the execution traces of LM programs.
We apply iterated decomposition to three real-world tasks and improve the
accuracy of LM programs over less compositional baselines: describing the
placebo used in a randomized controlled trial (25% to 65%), evaluating
participant adherence to a medical intervention (53% to 70%), and answering NLP
questions on the Qasper dataset (38% to 69%). These applications serve as case
studies for a workflow that, if automated, could keep ML systems interpretable
and safe even as they scale to increasingly complex tasks.