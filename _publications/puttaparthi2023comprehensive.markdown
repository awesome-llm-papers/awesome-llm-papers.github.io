---
layout: publication
title: Comprehensive Evaluation Of Chatgpt Reliability Through Multilingual Inquiries
authors: Puttaparthi et al.
conference: 'Findings of the Association for Computational Linguistics: EMNLP 2023'
year: 2023
bibkey: puttaparthi2023comprehensive
citations: 74
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2312.10524'}]
tags: [Security, Model Architecture, Prompting, Evaluation, ACL, EMNLP, GPT, Reinforcement
    Learning]
---
ChatGPT is currently the most popular large language model (LLM), with over
100 million users, making a significant impact on people's lives. However, due
to the presence of jailbreak vulnerabilities, ChatGPT might have negative
effects on people's lives, potentially even facilitating criminal activities.
Testing whether ChatGPT can cause jailbreak is crucial because it can enhance
ChatGPT's security, reliability, and social responsibility. Inspired by
previous research revealing the varied performance of LLMs in different
language translations, we suspected that wrapping prompts in multiple languages
might lead to ChatGPT jailbreak. To investigate this, we designed a study with
a fuzzing testing approach to analyzing ChatGPT's cross-linguistic proficiency.
Our study includes three strategies by automatically posing different formats
of malicious questions to ChatGPT: (1) each malicious question involving only
one language, (2) multilingual malicious questions, (3) specifying that ChatGPT
responds in a language different from the prompts. In addition, we also combine
our strategies by utilizing prompt injection templates to wrap the three
aforementioned types of questions. We examined a total of 7,892 Q&A data
points, discovering that multilingual wrapping can indeed lead to ChatGPT's
jailbreak, with different wrapping methods having varying effects on jailbreak
probability. Prompt injection can amplify the probability of jailbreak caused
by multilingual wrapping. This work provides insights for OpenAI developers to
enhance ChatGPT's support for language diversity and inclusion.