---
layout: publication
title: Repository Structure-aware Training Makes Slms Better Issue Resolver
authors: Ma et al.
conference: 'Proceedings of the 60th Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)'
year: 2024
bibkey: ma2024repository
citations: 93
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2412.19031'}]
tags: [ACL, Training Techniques, Evaluation]
---
Language models have been applied to various software development tasks, but
the performance varies according to the scale of the models. Large Language
Models (LLMs) outperform Small Language Models (SLMs) in complex tasks like
repository-level issue resolving, but raise concerns about privacy and cost. In
contrast, SLMs are more accessible but under-perform in complex tasks. In this
paper, we introduce ReSAT (Repository Structure-Aware Training), construct
training data based on a large number of issues and corresponding pull requests
from open-source communities to enhance the model's understanding of repository
structure and issue resolving ability. We construct two types of training data:
(1) localization training data, a multi-level progressive localization data to
improve code understanding and localization capability; (2) code edit training
data, which improves context-based code editing capability. The evaluation
results on SWE-Bench-verified and RepoQA demonstrate that ReSAT effectively
enhances SLMs' issue-resolving and repository-level long-context understanding
capabilities.