---
layout: publication
title: 'Lost At C: A User Study On The Security Implications Of Large Language Model
  Code Assistants'
authors: Gustavo Sandoval et al.
conference: Arxiv
year: 2022
citations: 25
bibkey: sandoval2022lost
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2208.09727'}]
tags: [Tools, Security, Reinforcement Learning]
---
Large Language Models (LLMs) such as OpenAI Codex are increasingly being used
as AI-based coding assistants. Understanding the impact of these tools on
developers' code is paramount, especially as recent work showed that LLMs may
suggest cybersecurity vulnerabilities. We conduct a security-driven user study
(N=58) to assess code written by student programmers when assisted by LLMs.
Given the potential severity of low-level bugs as well as their relative
frequency in real-world projects, we tasked participants with implementing a
singly-linked 'shopping list' structure in C. Our results indicate that the
security impact in this setting (low-level C with pointer and array
manipulations) is small: AI-assisted users produce critical security bugs at a
rate no greater than 10% more than the control, indicating the use of LLMs does
not introduce new security risks.