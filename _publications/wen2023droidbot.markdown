---
layout: publication
title: 'Droidbot-gpt: Gpt-powered UI Automation For Android'
authors: Wen et al.
conference: 2017 IEEE/ACM 39th International Conference on Software Engineering Companion
  (ICSE-C)
year: 2023
bibkey: wen2023droidbot
citations: 92
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2304.07061'}]
tags: [Model Architecture, Prompting, Training Techniques, LLM For Code, Applications,
  LLM for Code, RAG, GPT, Datasets]
---
This paper introduces DroidBot-GPT, a tool that utilizes GPT-like large
language models (LLMs) to automate the interactions with Android mobile
applications. Given a natural language description of a desired task,
DroidBot-GPT can automatically generate and execute actions that navigate the
app to complete the task. It works by translating the app GUI state information
and the available actions on the smartphone screen to natural language prompts
and asking the LLM to make a choice of actions. Since the LLM is typically
trained on a large amount of data including the how-to manuals of diverse
software applications, it has the ability to make reasonable choices of actions
based on the provided information. We evaluate DroidBot-GPT with a self-created
dataset that contains 33 tasks collected from 17 Android applications spanning
10 categories. It can successfully complete 39.39% of the tasks, and the
average partial completion progress is about 66.76%. Given the fact that our
method is fully unsupervised (no modification required from both the app and
the LLM), we believe there is great potential to enhance automation performance
with better app development paradigms and/or custom model training.