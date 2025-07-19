---
layout: publication
title: 'Multi-task Learning With Llms For Implicit Sentiment Analysis: Data-level
  And Task-level Automatic Weight Learning'
authors: Lai et al.
conference: Proceedings of the AAAI Conference on Artificial Intelligence
year: 2024
bibkey: lai2024multi
citations: 56
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2412.09046'}]
tags: [RAG, Tools, AAAI, Reinforcement Learning]
---
Implicit sentiment analysis (ISA) presents significant challenges due to the
absence of salient cue words. Previous methods have struggled with insufficient
data and limited reasoning capabilities to infer underlying opinions.
Integrating multi-task learning (MTL) with large language models (LLMs) offers
the potential to enable models of varying sizes to reliably perceive and
recognize genuine opinions in ISA. However, existing MTL approaches are
constrained by two sources of uncertainty: data-level uncertainty, arising from
hallucination problems in LLM-generated contextual information, and task-level
uncertainty, stemming from the varying capacities of models to process
contextual information. To handle these uncertainties, we introduce MT-ISA, a
novel MTL framework that enhances ISA by leveraging the generation and
reasoning capabilities of LLMs through automatic MTL. Specifically, MT-ISA
constructs auxiliary tasks using generative LLMs to supplement sentiment
elements and incorporates automatic MTL to fully exploit auxiliary data. We
introduce data-level and task-level automatic weight learning (AWL), which
dynamically identifies relationships and prioritizes more reliable data and
critical tasks, enabling models of varying sizes to adaptively learn
fine-grained weights based on their reasoning capabilities. We investigate
three strategies for data-level AWL, while also introducing homoscedastic
uncertainty for task-level AWL. Extensive experiments reveal that models of
varying sizes achieve an optimal balance between primary prediction and
auxiliary tasks in MT-ISA. This underscores the effectiveness and adaptability
of our approach.