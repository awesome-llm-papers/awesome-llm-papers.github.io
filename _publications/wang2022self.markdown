---
layout: publication
title: Self-consistency Improves Chain Of Thought Reasoning In Language Models
authors: Xuezhi Wang et al.
conference: Arxiv
year: 2022
citations: 462
bibkey: wang2022self
additional_links: [{name: Paper, url: 'http://arxiv.org/abs/2203.11171v4'}]
tags: [RAG, Prompting, Evaluation]
---
Chain-of-thought prompting combined with pre-trained large language models
has achieved encouraging results on complex reasoning tasks. In this paper, we
propose a new decoding strategy, self-consistency, to replace the naive greedy
decoding used in chain-of-thought prompting. It first samples a diverse set of
reasoning paths instead of only taking the greedy one, and then selects the
most consistent answer by marginalizing out the sampled reasoning paths.
Self-consistency leverages the intuition that a complex reasoning problem
typically admits multiple different ways of thinking leading to its unique
correct answer. Our extensive empirical evaluation shows that self-consistency
boosts the performance of chain-of-thought prompting with a striking margin on
a range of popular arithmetic and commonsense reasoning benchmarks, including
GSM8K (+17.9%), SVAMP (+11.0%), AQuA (+12.2%), StrategyQA (+6.4%) and
ARC-challenge (+3.9%).