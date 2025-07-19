---
layout: publication
title: Curiosity-driven Red-teaming For Large Language Models
authors: Hong et al.
conference: Proceedings of the 2022 Conference on Empirical Methods in Natural Language
  Processing
year: 2024
bibkey: hong2024curiosity
citations: 98
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2402.19464'}]
tags: [RAG, EMNLP, Training Techniques, Prompting, Agentic, Reinforcement Learning,
  Applications, Fine Tuning]
---
Large language models (LLMs) hold great potential for many natural language
applications but risk generating incorrect or toxic content. To probe when an
LLM generates unwanted content, the current paradigm is to recruit a
\textit\{red team\} of human testers to design input prompts (i.e., test cases)
that elicit undesirable responses from LLMs. However, relying solely on human
testers is expensive and time-consuming. Recent works automate red teaming by
training a separate red team LLM with reinforcement learning (RL) to generate
test cases that maximize the chance of eliciting undesirable responses from the
target LLM. However, current RL methods are only able to generate a small
number of effective test cases resulting in a low coverage of the span of
prompts that elicit undesirable responses from the target LLM. To overcome this
limitation, we draw a connection between the problem of increasing the coverage
of generated test cases and the well-studied approach of curiosity-driven
exploration that optimizes for novelty. Our method of curiosity-driven red
teaming (CRT) achieves greater coverage of test cases while mantaining or
increasing their effectiveness compared to existing methods. Our method, CRT
successfully provokes toxic responses from LLaMA2 model that has been heavily
fine-tuned using human preferences to avoid toxic outputs. Code is available at
https://github.com/Improbable-AI/curiosity_redteam