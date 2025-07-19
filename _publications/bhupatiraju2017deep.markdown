---
layout: publication
title: 'Deep API Programmer: Learning To Program With Apis'
authors: Bhupatiraju et al.
conference: Proceedings of the 2016 24th ACM SIGSOFT International Symposium on Foundations
  of Software Engineering
year: 2017
bibkey: bhupatiraju2017deep
citations: 385
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1704.04327'}]
tags: [Model Architecture, Tools, Evaluation, LLM For Code, LLM for Code, Datasets,
  Reinforcement Learning]
---
We present DAPIP, a Programming-By-Example system that learns to program with
APIs to perform data transformation tasks. We design a domain-specific language
(DSL) that allows for arbitrary concatenations of API outputs and constant
strings. The DSL consists of three family of APIs: regular expression-based
APIs, lookup APIs, and transformation APIs. We then present a novel neural
synthesis algorithm to search for programs in the DSL that are consistent with
a given set of examples. The search algorithm uses recently introduced neural
architectures to encode input-output examples and to model the program search
in the DSL. We show that synthesis algorithm outperforms baseline methods for
synthesizing programs on both synthetic and real-world benchmarks.