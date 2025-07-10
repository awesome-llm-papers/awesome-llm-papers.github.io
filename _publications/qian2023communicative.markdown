---
layout: publication
title: 'Chatdev: Communicative Agents For Software Development'
authors: Chen Qian et al.
conference: 'Proceedings of the 62nd Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)'
year: 2023
citations: 56
bibkey: qian2023communicative
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2307.07924'}, {name: Code,
    url: 'https://github.com/OpenBMB/ChatDev'}]
tags: [Agentic, Tools, Has Code, RAG]
---
Software development is a complex task that necessitates cooperation among
multiple members with diverse skills. Numerous studies used deep learning to
improve specific phases in a waterfall model, such as design, coding, and
testing. However, the deep learning model in each phase requires unique
designs, leading to technical inconsistencies across various phases, which
results in a fragmented and ineffective development process. In this paper, we
introduce ChatDev, a chat-powered software development framework in which
specialized agents driven by large language models (LLMs) are guided in what to
communicate (via chat chain) and how to communicate (via communicative
dehallucination). These agents actively contribute to the design, coding, and
testing phases through unified language-based communication, with solutions
derived from their multi-turn dialogues. We found their utilization of natural
language is advantageous for system design, and communicating in programming
language proves helpful in debugging. This paradigm demonstrates how linguistic
communication facilitates multi-agent collaboration, establishing language as a
unifying bridge for autonomous task-solving among LLM agents. The code and data
are available at https://github.com/OpenBMB/ChatDev.