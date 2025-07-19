---
layout: publication
title: A Survey On The Optimization Of Large Language Model-based Agents
authors: Du et al.
conference: Frontiers of Computer Science
year: 2025
bibkey: du2025survey
citations: 382
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2503.12434'}]
tags: [RAG, Training Techniques, Alt, Prompting, Agentic, Tools, Evaluation, Survey
    Paper, Efficiency And Optimization, Reinforcement Learning, Applications, Fine
    Tuning, Datasets]
---
With the rapid development of Large Language Models (LLMs), LLM-based agents
have been widely adopted in various fields, becoming essential for autonomous
decision-making and interactive tasks. However, current work typically relies
on prompt design or fine-tuning strategies applied to vanilla LLMs, which often
leads to limited effectiveness or suboptimal performance in complex
agent-related environments. Although LLM optimization techniques can improve
model performance across many general tasks, they lack specialized optimization
towards critical agent functionalities such as long-term planning, dynamic
environmental interaction, and complex decision-making. Although numerous
recent studies have explored various strategies to optimize LLM-based agents
for complex agent tasks, a systematic review summarizing and comparing these
methods from a holistic perspective is still lacking. In this survey, we
provide a comprehensive review of LLM-based agent optimization approaches,
categorizing them into parameter-driven and parameter-free methods. We first
focus on parameter-driven optimization, covering fine-tuning-based
optimization, reinforcement learning-based optimization, and hybrid strategies,
analyzing key aspects such as trajectory data construction, fine-tuning
techniques, reward function design, and optimization algorithms. Additionally,
we briefly discuss parameter-free strategies that optimize agent behavior
through prompt engineering and external knowledge retrieval. Finally, we
summarize the datasets and benchmarks used for evaluation and tuning, review
key applications of LLM-based agents, and discuss major challenges and
promising future directions. Our repository for related references is available
at https://github.com/YoungDubbyDu/LLM-Agent-Optimization.