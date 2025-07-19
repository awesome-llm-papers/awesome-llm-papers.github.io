---
layout: publication
title: 'Longfunceval: Measuring The Effectiveness Of Long Context Models For Function
  Calling'
authors: Kate et al.
conference: Proceedings of the 22nd annual ACM SIGPLAN conference on Object-oriented
  programming systems, languages and applications
year: 2025
bibkey: kate2025longfunceval
citations: 77
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2505.10570'}]
tags: [Tools, Evaluation, Reinforcement Learning, Applications, Datasets]
---
Multiple recent studies have documented large language models' (LLMs) performance on calling external tools/functions. Others focused on LLMs' abilities to handle longer context lengths. At the intersection of these areas lies another interesting problem: LLMs' abilities to accurately perform function calls in long context settings. Particularly, when calling tools, LLMs are encumbered by three predominant challenges: (1) a large catalog of tools, (2) long responses from the tool APIs, and (3) long multi-turn conversations. These challenges are particularly relevant to enterprise applications of LLMs which engage in multi-turn conversations with users to complete complex tasks that require a large catalog of complex tools. The literature contains multiple investigations of long context challenges such as lost in the middle or needle in the haystack for natural language tasks. In this paper, we make the first attempt to comprehensively study the long context understanding capabilities of these models in the tool calling setup. We modify existing benchmarks for challenge 1 and 3, and create a new evaluation set for challenge 2 to enable this analysis. We gradually increase the input context length and also vary the position of the answer in the input. When evaluated with several long context models, we observe a performance drop of 7% to 85% as the number of tools increases, a 7% to 91% degradation in answer retrieval as the tool responses length increases, and 13% and 40% degradation for as multi-turn conversations get longer. Our study shows that LLMs still struggle with long context in tool calling settings, motivating future research to drive further LLM improvements.