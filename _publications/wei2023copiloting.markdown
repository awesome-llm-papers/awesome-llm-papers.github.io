---
layout: publication
title: 'Copiloting The Copilots: Fusing Large Language Models With Completion Engines
  For Automated Program Repair'
authors: Yuxiang Wei, Chunqiu Steven Xia, Lingming Zhang
conference: Arxiv
year: 2023
citations: 40
bibkey: wei2023copiloting
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2309.00608'}]
tags: [RAG, Tools, GPT, Reinforcement Learning]
---
During Automated Program Repair (APR), it can be challenging to synthesize
correct patches for real-world systems in general-purpose programming
languages. Recent Large Language Models (LLMs) have been shown to be helpful
"copilots" in assisting developers with various coding tasks, and have also
been directly applied for patch synthesis. However, most LLMs treat programs as
sequences of tokens, meaning that they are ignorant of the underlying semantics
constraints of the target programming language. This results in plenty of
statically invalid generated patches, impeding the practicality of the
technique. Therefore, we propose Repilot, a general code generation framework
to further copilot the AI "copilots" (i.e., LLMs) by synthesizing more valid
patches during the repair process. Our key insight is that many LLMs produce
outputs autoregressively (i.e., token by token), resembling human writing
programs, which can be significantly boosted and guided through a Completion
Engine. Repilot synergistically synthesizes a candidate patch through the
interaction between an LLM and a Completion Engine, which 1) prunes away
infeasible tokens suggested by the LLM and 2) proactively completes the token
based on the suggestions provided by the Completion Engine. Our evaluation on a
subset of the widely-used Defects4j 1.2 and 2.0 datasets shows that Repilot
outperforms state-of-the-art techniques by fixing 27% and 47% more bugs,
respectively. Moreover, Repilot produces more valid and correct patches than
the base LLM with the same budget. While we focus on leveraging Repilot for APR
in this work, the overall approach is also generalizable to other code
generation tasks.