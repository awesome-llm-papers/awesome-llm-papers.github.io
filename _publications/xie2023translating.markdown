---
layout: publication
title: Translating Natural Language To Planning Goals With Large-language Models
authors: Yaqi Xie et al.
conference: Arxiv
year: 2023
citations: 38
bibkey: xie2023translating
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2302.05128'}]
tags: [GPT, RAG, Model Architecture, Prompting]
---
Recent large language models (LLMs) have demonstrated remarkable performance
on a variety of natural language processing (NLP) tasks, leading to intense
excitement about their applicability across various domains. Unfortunately,
recent work has also shown that LLMs are unable to perform accurate reasoning
nor solve planning problems, which may limit their usefulness for
robotics-related tasks. In this work, our central question is whether LLMs are
able to translate goals specified in natural language to a structured planning
language. If so, LLM can act as a natural interface between the planner and
human users; the translated goal can be handed to domain-independent AI
planners that are very effective at planning. Our empirical results on GPT 3.5
variants show that LLMs are much better suited towards translation rather than
planning. We find that LLMs are able to leverage commonsense knowledge and
reasoning to furnish missing details from under-specified goals (as is often
the case in natural language). However, our experiments also reveal that LLMs
can fail to generate goals in tasks that involve numerical or physical (e.g.,
spatial) reasoning, and that LLMs are sensitive to the prompts used. As such,
these models are promising for translation to structured planning languages,
but care should be taken in their use.