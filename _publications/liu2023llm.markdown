---
layout: publication
title: 'LLM+P: Empowering Large Language Models With Optimal Planning Proficiency'
authors: Liu et al.
conference: Arxiv
year: 2023
bibkey: liu2023llm
citations: 68
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2304.11477'}]
tags: [RAG, Tools, Evaluation, Reinforcement Learning, Datasets]
---
Large language models (LLMs) have demonstrated remarkable zero-shot
generalization abilities: state-of-the-art chatbots can provide plausible
answers to many common questions that arise in daily life. However, so far,
LLMs cannot reliably solve long-horizon planning problems. By contrast,
classical planners, once a problem is given in a formatted way, can use
efficient search algorithms to quickly identify correct, or even optimal,
plans. In an effort to get the best of both worlds, this paper introduces
LLM+P, the first framework that incorporates the strengths of classical
planners into LLMs. LLM+P takes in a natural language description of a planning
problem, then returns a correct (or optimal) plan for solving that problem in
natural language. LLM+P does so by first converting the language description
into a file written in the planning domain definition language (PDDL), then
leveraging classical planners to quickly find a solution, and then translating
the found solution back into natural language. Along with LLM+P, we define a
diverse set of different benchmark problems taken from common planning
scenarios. Via a comprehensive set of experiments on these benchmark problems,
we find that LLM+P is able to provide optimal solutions for most problems,
while LLMs fail to provide even feasible plans for most problems.\footnote\{The
code and results are publicly available at
https://github.com/Cranial-XIX/llm-pddl.git.