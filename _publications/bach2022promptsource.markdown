---
layout: publication
title: 'Promptsource: An Integrated Development Environment And Repository For Natural
  Language Prompts'
authors: Stephen H. Bach, Victor Sanh, Zheng-xin Yong, Albert Webson, Colin Raffel,
  Nihal V. Nayak, Abheesht Sharma, Taewoon Kim, M Saiful Bari, Thibault Fevry, Zaid
  Alyafeai, Manan Dey, Andrea Santilli, Zhiqing Sun, Srulik Ben-david, Canwen Xu,
  Gunjan Chhablani, Han Wang, Jason Alan Fries, Maged S. Al-shaibani, Shanya Sharma,
  Urmish Thakker, Khalid Almubarak, Xiangru Tang, Dragomir Radev, Mike Tian-jian Jiang,
  Alexander M. Rush
conference: 'Proceedings of the 60th Annual Meeting of the Association for Computational
  Linguistics: System Demonstrations'
year: 2022
bibkey: bach2022promptsource
citations: 133
additional_links: [{name: Code, url: 'https://github.com/bigscience-workshop/promptsource'},
  {name: Paper, url: 'https://arxiv.org/abs/2202.01279'}]
tags: ["Has Code", "Tools"]
short_authors: Bach et al.
---
PromptSource is a system for creating, sharing, and using natural language
prompts. Prompts are functions that map an example from a dataset to a natural
language input and target output. Using prompts to train and query language
models is an emerging area in NLP that requires new tools that let users
develop and refine these prompts collaboratively. PromptSource addresses the
emergent challenges in this new setting with (1) a templating language for
defining data-linked prompts, (2) an interface that lets users quickly iterate
on prompt development by observing outputs of their prompts on many examples,
and (3) a community-driven set of guidelines for contributing new prompts to a
common pool. Over 2,000 prompts for roughly 170 datasets are already available
in PromptSource. PromptSource is available at
https://github.com/bigscience-workshop/promptsource.