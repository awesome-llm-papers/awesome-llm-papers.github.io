---
layout: publication
title: Towards Practical Defect-focused Automated Code Review
authors: Lu et al.
conference: Proceedings Third International Workshop on Policies for Distributed Systems
  and Networks
year: 2025
bibkey: lu2025towards
citations: 109
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2505.17928'}]
tags: [RAG, Prompting, Tools, Evaluation, Language Modeling, Reinforcement Learning,
  LLM For Code]
---
The complexity of code reviews has driven efforts to automate review comments, but prior approaches oversimplify this task by treating it as snippet-level code-to-text generation and relying on text similarity metrics like BLEU for evaluation. These methods overlook repository context, real-world merge request evaluation, and defect detection, limiting their practicality. To address these issues, we explore the full automation pipeline within the online recommendation service of a company with nearly 400 million daily active users, analyzing industry-grade C++ codebases comprising hundreds of thousands of lines of code. We identify four key challenges: 1) capturing relevant context, 2) improving key bug inclusion (KBI), 3) reducing false alarm rates (FAR), and 4) integrating human workflows. To tackle these, we propose 1) code slicing algorithms for context extraction, 2) a multi-role LLM framework for KBI, 3) a filtering mechanism for FAR reduction, and 4) a novel prompt design for better human interaction. Our approach, validated on real-world merge requests from historical fault reports, achieves a 2x improvement over standard LLMs and a 10x gain over previous baselines. While the presented results focus on C++, the underlying framework design leverages language-agnostic principles (e.g., AST-based analysis), suggesting potential for broader applicability.