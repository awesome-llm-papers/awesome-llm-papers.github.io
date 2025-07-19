---
layout: publication
title: 'What Makes In-context Learning Effective For Mathematical Reasoning: A Theoretical
  Analysis'
authors: Liu et al.
conference: Communications of the ACM
year: 2024
bibkey: liu2024what
citations: 106
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2412.12157'}]
tags: [Few Shot, Evaluation, Datasets, In Context Learning]
---
Owing to the capability of in-context learning, large language models (LLMs)
have shown impressive performance across diverse mathematical reasoning
benchmarks. However, we find that few-shot demonstrations can sometimes bring
negative performance and their effectiveness on LLMs' reasoning abilities
remains unreliable. To this end, in this paper, we aim to theoretically analyze
the impact of in-context demonstrations on LLMs' reasoning performance. We
prove that the reasoning efficacy (measured by empirical prediction loss) can
be bounded by a LLM-oriented semantic similarity and an inference stability of
demonstrations, which is general for both one-shot and few-shot scenarios.
Based on this finding, we propose a straightforward, generalizable, and
low-complexity demonstration selection method named LMS3. It can adaptively
facilitate to select the most pertinent samples for different LLMs and includes
a novel demonstration rejection mechanism to automatically filter out samples
that are unsuitable for few-shot learning. Through experiments on three
representative benchmarks, two LLM backbones, and multiple few-shot settings,
we verify that our LMS3 has superiority and achieves consistent improvements on
all datasets, which existing methods have been unable to accomplish.