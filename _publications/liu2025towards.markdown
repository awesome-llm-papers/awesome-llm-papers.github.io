---
layout: publication
title: Towards Secure Program Partitioning For Smart Contracts With Llm's In-context
  Learning
authors: Liu et al.
conference: ACM Transactions on Computer Systems
year: 2025
bibkey: liu2025towards
citations: 96
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2502.14215'}]
tags: [GPT, In Context Learning, Model Architecture, Reinforcement Learning, Security,
  LLM For Code]
---
Smart contracts are highly susceptible to manipulation attacks due to the
leakage of sensitive information. Addressing manipulation vulnerabilities is
particularly challenging because they stem from inherent data confidentiality
issues rather than straightforward implementation bugs. To tackle this by
preventing sensitive information leakage, we present PartitionGPT, the first
LLM-driven approach that combines static analysis with the in-context learning
capabilities of large language models (LLMs) to partition smart contracts into
privileged and normal codebases, guided by a few annotated sensitive data
variables. We evaluated PartitionGPT on 18 annotated smart contracts containing
99 sensitive functions. The results demonstrate that PartitionGPT successfully
generates compilable, and verified partitions for 78% of the sensitive
functions while reducing approximately 30% code compared to function-level
partitioning approach. Furthermore, we evaluated PartitionGPT on nine
real-world manipulation attacks that lead to a total loss of 25 million
dollars, PartitionGPT effectively prevents eight cases, highlighting its
potential for broad applicability and the necessity for secure program
partitioning during smart contract development to diminish manipulation
vulnerabilities.