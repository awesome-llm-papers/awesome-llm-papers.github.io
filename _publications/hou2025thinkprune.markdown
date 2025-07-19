---
layout: publication
title: 'Thinkprune: Pruning Long Chain-of-thought Of Llms Via Reinforcement Learning'
authors: Hou et al.
conference: Neurocomputing
year: 2025
bibkey: hou2025thinkprune
citations: 73
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2504.01296'}]
tags: [Agentic, Efficiency And Optimization, Reinforcement Learning, Fine Tuning,
  Pruning, Datasets]
---
We present ThinkPrune, a simple yet effective method for pruning the thinking
length for long-thinking LLMs, which has been found to often produce
inefficient and redundant thinking processes. Existing preliminary explorations
of reducing thinking length primarily focus on forcing the thinking process to
early exit, rather than adapting the LLM to optimize and consolidate the
thinking process, and therefore the length-performance tradeoff observed so far
is sub-optimal. To fill this gap, ThinkPrune offers a simple solution that
continuously trains the long-thinking LLMs via reinforcement learning (RL) with
an added token limit, beyond which any unfinished thoughts and answers will be
discarded, resulting in a zero reward. To further preserve model performance,
we introduce an iterative length pruning approach, where multiple rounds of RL
are conducted, each with an increasingly more stringent token limit. We
observed that ThinkPrune results in a remarkable performance-length tradeoff --
on the AIME24 dataset, the reasoning length of DeepSeek-R1-Distill-Qwen-1.5B
can be reduced by half with only 2% drop in performance. We also observed that
after pruning, the LLMs can bypass unnecessary steps while keeping the core
reasoning process complete. Code is available at
https://github.com/UCSB-NLP-Chang/ThinkPrune.