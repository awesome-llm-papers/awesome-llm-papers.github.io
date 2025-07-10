---
layout: publication
title: 'SOLAR 10.7B: Scaling Large Language Models With Simple Yet Effective Depth
  Up-scaling'
authors: Dahyun Kim et al.
conference: 'Proceedings of the 2024 Conference of the North American Chapter of the
  Association for Computational Linguistics: Human Language Technologies (Volume 6:
  Industry Track)'
year: 2023
citations: 22
bibkey: kim2023solar
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2312.15166'}]
tags: [Training Techniques]
---
We introduce SOLAR 10.7B, a large language model (LLM) with 10.7 billion
parameters, demonstrating superior performance in various natural language
processing (NLP) tasks. Inspired by recent efforts to efficiently up-scale
LLMs, we present a method for scaling LLMs called depth up-scaling (DUS), which
encompasses depthwise scaling and continued pretraining. In contrast to other
LLM up-scaling methods that use mixture-of-experts, DUS does not require
complex changes to train and inference efficiently. We show experimentally that
DUS is simple yet effective in scaling up high-performance LLMs from small
ones. Building on the DUS model, we additionally present SOLAR 10.7B-Instruct,
a variant fine-tuned for instruction-following capabilities, surpassing
Mixtral-8x7B-Instruct. SOLAR 10.7B is publicly available under the Apache 2.0
license, promoting broad access and application in the LLM field.