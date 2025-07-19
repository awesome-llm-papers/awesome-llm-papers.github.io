---
layout: publication
title: 'Demorank: Selecting Effective Demonstrations For Large Language Models In
  Ranking Task'
authors: Liu Wenhan, Zhu Yutao, Dou Zhicheng
conference: 'Findings of the Association for Computational Linguistics: NAACL 2024'
year: 2024
bibkey: liu2024demorank
citations: 68
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2406.16332'}]
tags: [ACL, Tools, Training Techniques, NAACL]
---
Recently, there has been increasing interest in applying large language
models (LLMs) as zero-shot passage rankers. However, few studies have explored
how to select appropriate in-context demonstrations for the passage ranking
task, which is the focus of this paper. Previous studies mainly use LLM's
feedback to train a retriever for demonstration selection. These studies apply
the LLM to score each demonstration independently, which ignores the
dependencies between demonstrations (especially important in ranking task),
leading to inferior performance of top-\\(k\\) retrieved demonstrations. To
mitigate this issue, we introduce a demonstration reranker to rerank the
retrieved demonstrations so that top-\\(k\\) ranked ones are more suitable for ICL.
However, generating training data for such reranker is quite challenging. On
the one hand, different from demonstration retriever, the training samples of
reranker need to incorporate demonstration dependencies. On the other hand,
obtaining the gold ranking from the retrieved demonstrations is an NP-hard
problem, which is hard to implement. To overcome these challenges, we propose a
method to approximate the optimal demonstration list iteratively and utilize
LLM to score demonstration lists of varying lengths. By doing so, the search
space is greatly reduced and demonstration dependencies are considered. Based
on these scored demonstration lists, we further design a list-pairwise training
approach which compares a pair of lists that only differ in the last
demonstration, to teach the reranker how to select the next demonstration given
a previous sequence. In this paper, we propose a demonstration selection
framework DemoRank for ranking task and conduct extensive experiments to prove
its strong ability.