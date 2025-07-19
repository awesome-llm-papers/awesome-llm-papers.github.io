---
layout: publication
title: Do Advanced Language Models Eliminate The Need For Prompt Engineering In Software
  Engineering?
authors: Wang et al.
conference: Algorithms for Intelligent Systems
year: 2024
bibkey: wang2024do
citations: 116
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2411.02093'}]
tags: [GPT, Prompting, Tools, Model Architecture, Reinforcement Learning, LLM For
    Code]
---
Large Language Models (LLMs) have significantly advanced software engineering
(SE) tasks, with prompt engineering techniques enhancing their performance in
code-related areas. However, the rapid development of foundational LLMs such as
the non-reasoning model GPT-4o and the reasoning model o1 raises questions
about the continued effectiveness of these prompt engineering techniques. This
paper presents an extensive empirical study that reevaluates various prompt
engineering techniques within the context of these advanced LLMs. Focusing on
three representative SE tasks, i.e., code generation, code translation, and
code summarization, we assess whether prompt engineering techniques still yield
improvements with advanced models, the actual effectiveness of reasoning models
compared to non-reasoning models, and whether the benefits of using these
advanced models justify their increased costs. Our findings reveal that prompt
engineering techniques developed for earlier LLMs may provide diminished
benefits or even hinder performance when applied to advanced models. In
reasoning LLMs, the ability of sophisticated built-in reasoning reduces the
impact of complex prompts, sometimes making simple zero-shot prompting more
effective. Furthermore, while reasoning models outperform non-reasoning models
in tasks requiring complex reasoning, they offer minimal advantages in tasks
that do not need reasoning and may incur unnecessary costs. Based on our study,
we provide practical guidance for practitioners on selecting appropriate prompt
engineering techniques and foundational LLMs, considering factors such as task
requirements, operational costs, and environmental impact. Our work contributes
to a deeper understanding of effectively harnessing advanced LLMs in SE tasks,
informing future research and application development.