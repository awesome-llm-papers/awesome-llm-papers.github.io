---
layout: publication
title: 'Geo-olm: Enabling Sustainable Earth Observation Studies With Cost-efficient
  Open Language Models & State-driven Workflows'
authors: Stamoulis Dimitrios, Marculescu Diana
conference: Transactions in GIS
year: 2025
bibkey: stamoulis2025geo
citations: 68
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2504.04319'}]
tags: [RAG, GPT, Agentic, Tools, Evaluation, Model Architecture, Applications, Datasets]
---
Geospatial Copilots hold immense potential for automating Earth observation
(EO) and climate monitoring workflows, yet their reliance on large-scale models
such as GPT-4o introduces a paradox: tools intended for sustainability studies
often incur unsustainable costs. Using agentic AI frameworks in geospatial
applications can amass thousands of dollars in API charges or requires
expensive, power-intensive GPUs for deployment, creating barriers for
researchers, policymakers, and NGOs. Unfortunately, when geospatial Copilots
are deployed with open language models (OLMs), performance often degrades due
to their dependence on GPT-optimized logic. In this paper, we present Geo-OLM,
a tool-augmented geospatial agent that leverages the novel paradigm of
state-driven LLM reasoning to decouple task progression from tool calling. By
alleviating the workflow reasoning burden, our approach enables low-resource
OLMs to complete geospatial tasks more effectively. When downsizing to small
models below 7B parameters, Geo-OLM outperforms the strongest prior geospatial
baselines by 32.8% in successful query completion rates. Our method performs
comparably to proprietary models achieving results within 10% of GPT-4o, while
reducing inference costs by two orders of magnitude from \\\(500-\\\)1000 to under
\$10. We present an in-depth analysis with geospatial downstream benchmarks,
providing key insights to help practitioners effectively deploy OLMs for EO
applications.