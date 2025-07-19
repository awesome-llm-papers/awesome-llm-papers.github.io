---
layout: publication
title: 'Patchtrack: A Comprehensive Analysis Of Chatgpt''s Influence On Pull Request
  Outcomes'
authors: Ogenrwot Daniel, Businge John
conference: 'Proceedings of the 40th International Conference on Software Engineering:
  Software Engineering in Practice'
year: 2025
bibkey: ogenrwot2025patchtrack
citations: 53
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2505.07700'}]
tags: [Ethics And Bias, Model Architecture, Tools, LLM For Code, LLM for Code, GPT,
  Reinforcement Learning]
---
The rapid adoption of large language models (LLMs) like ChatGPT in software development has introduced new ways for developers to interact with AI, particularly in pull request workflows. While prior research has examined AI-generated code quality, there is limited understanding of how ChatGPT is utilized in real-world pull request decision-making and how its suggestions influence patch integration and rejection. To explore these aspects, we analyze self-admitted ChatGPT usage (SACU), where developers explicitly disclose their reliance on ChatGPT within pull request discussions. Our study examines 338 pull requests (285 merged, 53 closed) across 255 GitHub repositories, containing 645 ChatGPT-generated code snippets and 3,486 patches. We introduce PatchTrack, a classification tool that determines whether ChatGPT-generated patches were applied (PA, 115 cases), not applied (PN, 64 cases), or not suggested (NE, 106 cases). Our findings reveal that full adoption of ChatGPT-generated code is rare, developers frequently modify or selectively integrate AI-generated patches to align with project constraints, with a median integration rate of 25%. Through qualitative analysis, we identify key factors influencing patch integration and pull request rejection, including scope misalignment, maintainability concerns, redundant solutions, and procedural barriers such as incomplete documentation or administrative policies. By providing empirical insights into ChatGPT's role in pull request workflows, this study informs developers, maintainers, and educators on the evolving use of generative AI in collaborative software development. It also lays the groundwork for future research on optimizing AI-assisted development, improving transparency in AI adoption, and enhancing patch integration workflows.