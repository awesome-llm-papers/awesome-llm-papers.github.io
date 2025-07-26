---
layout: publication
title: 'Swe-perf: Can Language Models Optimize Code Performance On Real-world Repositories?'
authors: Xinyi He, Qian Liu, Mingzhe Du, Lin Yan, Zhijie Fan, Yiming Huang, Zejian
  Yuan, Zejun Ma
conference: No Venue
year: 2025
bibkey: he2025swe
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/68788b9b001546c83aa4f9f5'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2507.12415'}]
tags: ["Efficiency", "Evaluation", "Has Code", "Llm For Code"]
short_authors: He et al.
---
Code performance optimization is paramount in real-world software engineering and critical for production-level systems. While Large Language Models (LLMs) have demonstrated impressive capabilities in code generation and bug fixing, their proficiency in enhancing code performance at the repository level remains largely unexplored. To address this gap, we introduce SWE-Perf, the first benchmark specifically designed to systematically evaluate LLMs on code performance optimization tasks within authentic repository contexts. SWE-Perf comprises 140 carefully curated instances, each derived from performance-improving pull requests from popular GitHub repositories. Each benchmark instance includes the relevant codebase, target functions, performance-related tests, expert-authored patches, and executable environments. Through a comprehensive evaluation of representative methods that span file-level and repo-level approaches (e.g., Agentless and OpenHands), we reveal a substantial capability gap between existing LLMs and expert-level optimization performance, highlighting critical research opportunities in this emerging field.

https://huggingface.co/discussions/paper/68788b9b001546c83aa4f9f5