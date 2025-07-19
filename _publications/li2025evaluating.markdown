---
layout: publication
title: 'Evaluating The Unseen Capabilities: How Many Theorems Do Llms Know?'
authors: Li et al.
conference: 'Proceedings of the Royal Society B: Biological Sciences'
year: 2025
bibkey: li2025evaluating
citations: 53
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2506.02058'}]
tags: [Tools, Evaluation, Applications]
---
Accurate evaluation of large language models (LLMs) is crucial for understanding their capabilities and guiding their development. However, current evaluations often inconsistently reflect the actual capacities of these models. In this paper, we demonstrate that one of many contributing factors to this \textit\{evaluation crisis\} is the oversight of unseen knowledge -- information encoded by LLMs but not directly observed or not yet observed during evaluations. We introduce KnowSum, a statistical framework designed to provide a more comprehensive assessment by quantifying the unseen knowledge for a class of evaluation tasks. KnowSum estimates the unobserved portion by extrapolating from the appearance frequencies of observed knowledge instances. We demonstrate the effectiveness and utility of KnowSum across three critical applications: estimating total knowledge, evaluating information retrieval effectiveness, and measuring output diversity. Our experiments reveal that a substantial volume of knowledge is omitted when relying solely on observed LLM performance. Importantly, KnowSum yields significantly different comparative rankings for several common LLMs based on their internal knowledge.