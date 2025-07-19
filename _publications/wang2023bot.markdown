---
layout: publication
title: Bot Or Human? Detecting Chatgpt Imposters With A Single Question
authors: Wang et al.
conference: Proceedings of the 27th International Conference on Evaluation and Assessment
  in Software Engineering
year: 2023
bibkey: wang2023bot
citations: 88
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2305.06424'}]
tags: [GPT, Tools, Evaluation, Model Architecture, Security, LLM For Code]
---
Large language models (LLMs) like GPT-4 have recently demonstrated impressive
capabilities in natural language understanding and generation. However, there
is a concern that they can be misused for malicious purposes, such as fraud or
denial-of-service attacks. Therefore, it is crucial to develop methods for
detecting whether the party involved in a conversation is a bot or a human. In
this paper, we propose a framework named FLAIR, Finding Large Language Model
Authenticity via a Single Inquiry and Response, to detect conversational bots
in an online manner. Specifically, we target a single question scenario that
can effectively differentiate human users from bots. The questions are divided
into two categories: those that are easy for humans but difficult for bots
(e.g., counting, substitution, searching, and ASCII art reasoning), and those
that are easy for bots but difficult for humans (e.g., memorization and
computation). Our approach shows different strengths of these questions in
their effectiveness, providing a new way for online service providers to
protect themselves against nefarious activities. Our code and question set are
available at https://github.com/hongwang600/FLAIR.