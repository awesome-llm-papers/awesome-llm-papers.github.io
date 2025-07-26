---
layout: publication
title: Deep Reinforcement Learning For Programming Language Correction
authors: Rahul Gupta, Aditya Kanade, Shirish Shevade
conference: Proceedings of the AAAI Conference on Artificial Intelligence
year: 2018
bibkey: gupta2018deep
citations: 185
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1801.10467'}]
tags: ["AAAI", "Reinforcement Learning"]
short_authors: Rahul Gupta, Aditya Kanade, Shirish Shevade
---
Novice programmers often struggle with the formal syntax of programming
languages. To assist them, we design a novel programming language correction
framework amenable to reinforcement learning. The framework allows an agent to
mimic human actions for text navigation and editing. We demonstrate that the
agent can be trained through self-exploration directly from the raw input, that
is, program text itself, without any knowledge of the formal syntax of the
programming language. We leverage expert demonstrations for one tenth of the
training data to accelerate training. The proposed technique is evaluated on
6975 erroneous C programs with typographic errors, written by students during
an introductory programming course. Our technique fixes 14% more programs and
29% more compiler error messages relative to those fixed by a state-of-the-art
tool, DeepFix, which uses a fully supervised neural machine translation
approach.