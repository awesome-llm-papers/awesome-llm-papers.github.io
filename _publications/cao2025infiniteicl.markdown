---
layout: publication
title: 'Infiniteicl: Breaking The Limit Of Context Window Size Via Long Short-term
  Memory Transformation'
authors: Cao Bowen, Cai Deng, Lam Wai
conference: 2017 3rd IEEE International Conference on Computer and Communications
  (ICCC)
year: 2025
bibkey: cao2025infiniteicl
citations: 58
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2504.01707'}]
tags: [RAG, Prompting, Tools, Evaluation, In Context Learning, Efficiency And Optimization,
  Reinforcement Learning]
---
In-context learning (ICL) is critical for large language models (LLMs), but
its effectiveness is constrained by finite context windows, particularly in
ultra-long contexts. To overcome this, we introduce InfiniteICL, a framework
that parallels context and parameters in LLMs with short- and long-term memory
in human cognitive systems, focusing on transforming temporary context
knowledge into permanent parameter updates. This approach significantly reduces
memory usage, maintains robust performance across varying input lengths, and
theoretically enables infinite context integration through the principles of
context knowledge elicitation, selection, and consolidation. Evaluations
demonstrate that our method reduces context length by 90% while achieving 103%
average performance of full-context prompting across fact recall, grounded
reasoning, and skill acquisition tasks. When conducting sequential multi-turn
transformations on complex, real-world contexts (with length up to 2M tokens),
our approach surpasses full-context prompting while using only 0.4% of the
original contexts. These findings highlight InfiniteICL's potential to enhance
the scalability and efficiency of LLMs by breaking the limitations of
conventional context window sizes.