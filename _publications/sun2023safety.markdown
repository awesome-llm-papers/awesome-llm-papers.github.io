---
layout: publication
title: Safety Assessment Of Chinese Large Language Models
authors: Hao Sun, Zhexin Zhang, Jiawen Deng, Jiale Cheng, Minlie Huang
conference: Arxiv
year: 2023
citations: 15
bibkey: sun2023safety
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2304.10436'}]
tags: [Responsible AI, Security, Model Architecture, Attention Mechanism, Tools, Reinforcement
    Learning, Prompting, GPT, Evaluation]
---
With the rapid popularity of large language models such as ChatGPT and GPT-4,
a growing amount of attention is paid to their safety concerns. These models
may generate insulting and discriminatory content, reflect incorrect social
values, and may be used for malicious purposes such as fraud and dissemination
of misleading information. Evaluating and enhancing their safety is
particularly essential for the wide application of large language models
(LLMs). To further promote the safe deployment of LLMs, we develop a Chinese
LLM safety assessment benchmark. Our benchmark explores the comprehensive
safety performance of LLMs from two perspectives: 8 kinds of typical safety
scenarios and 6 types of more challenging instruction attacks. Our benchmark is
based on a straightforward process in which it provides the test prompts and
evaluates the safety of the generated responses from the evaluated model. In
evaluation, we utilize the LLM's strong evaluation ability and develop it as a
safety evaluator by prompting. On top of this benchmark, we conduct safety
assessments and analyze 15 LLMs including the OpenAI GPT series and other
well-known Chinese LLMs, where we observe some interesting findings. For
example, we find that instruction attacks are more likely to expose safety
issues of all LLMs. Moreover, to promote the development and deployment of
safe, responsible, and ethical AI, we publicly release SafetyPrompts including
100k augmented prompts and responses by LLMs.