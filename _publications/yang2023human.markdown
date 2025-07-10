---
layout: publication
title: Human-centric Autonomous Systems With Llms For User Command Reasoning
authors: Yi Yang et al.
conference: 2024 IEEE/CVF Winter Conference on Applications of Computer Vision Workshops
  (WACVW)
year: 2023
citations: 15
bibkey: yang2023human
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2311.08206'}, {name: Code,
    url: 'https://github.com/KTH-RPL/DriveCmd_LLM'}]
tags: [Has Code, Few-Shot, RAG, Reinforcement Learning, Prompting]
---
The evolution of autonomous driving has made remarkable advancements in
recent years, evolving into a tangible reality. However, a human-centric
large-scale adoption hinges on meeting a variety of multifaceted requirements.
To ensure that the autonomous system meets the user's intent, it is essential
to accurately discern and interpret user commands, especially in complex or
emergency situations. To this end, we propose to leverage the reasoning
capabilities of Large Language Models (LLMs) to infer system requirements from
in-cabin users' commands. Through a series of experiments that include
different LLM models and prompt designs, we explore the few-shot multivariate
binary classification accuracy of system requirements from natural language
textual commands. We confirm the general ability of LLMs to understand and
reason about prompts but underline that their effectiveness is conditioned on
the quality of both the LLM model and the design of appropriate sequential
prompts. Code and models are public with the link
https://github.com/KTH-RPL/DriveCmd_LLM.