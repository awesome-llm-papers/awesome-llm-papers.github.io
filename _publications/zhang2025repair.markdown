---
layout: publication
title: 'Repair Ingredients Are All You Need: Improving Large Language Model-based
  Program Repair Via Repair Ingredients Search'
authors: Zhang et al.
conference: 2018 25th Asia-Pacific Software Engineering Conference (APSEC)
year: 2025
bibkey: zhang2025repair
citations: 50
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2506.23100'}]
tags: [Tools, Evaluation, LLM For Code, LLM for Code, RAG, Datasets, Reinforcement
    Learning]
---
Automated Program Repair (APR) techniques aim to automatically fix buggy programs. Among these, Large Language Model-based (LLM-based) approaches have shown great promise. Recent advances demonstrate that directly leveraging LLMs can achieve leading results. However, these techniques remain suboptimal in generating contextually relevant and accurate patches, as they often overlook repair ingredients crucial for practical program repair. In this paper, we propose ReinFix, a novel framework that enables LLMs to autonomously search for repair ingredients throughout both the reasoning and solution phases of bug fixing. In the reasoning phase, ReinFix integrates static analysis tools to retrieve internal ingredients, such as variable definitions, to assist the LLM in root cause analysis when it encounters difficulty understanding the context. During the solution phase, when the LLM lacks experience in fixing specific bugs, ReinFix searches for external ingredients from historical bug fixes with similar bug patterns, leveraging both the buggy code and its root cause to guide the LLM in identifying appropriate repair actions, thereby increasing the likelihood of generating correct patches. Evaluations on two popular benchmarks (Defects4J V1.2 and V2.0) demonstrate the effectiveness of our approach over SOTA baselines. Notably, ReinFix fixes 146 bugs, which is 32 more than the baselines on Defects4J V1.2. On Defects4J V2.0, ReinFix fixes 38 more bugs than the SOTA. Importantly, when evaluating on the recent benchmarks that are free of data leakage risk, ReinFix also maintains the best performance.