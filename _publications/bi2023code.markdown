---
layout: publication
title: 'Codekgc: Code Language Model For Generative Knowledge Graph Construction'
authors: Zhen Bi et al.
conference: ACM Transactions on Asian and Low-Resource Language Information Processing
year: 2023
citations: 24
bibkey: bi2023code
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2304.09048'}, {name: Code,
    url: 'https://github.com/zjunlp/DeepKE/tree/main/example/llm'}]
tags: [Has Code, Prompting, Evaluation]
---
Current generative knowledge graph construction approaches usually fail to
capture structural knowledge by simply flattening natural language into
serialized texts or a specification language. However, large generative
language model trained on structured data such as code has demonstrated
impressive capability in understanding natural language for structural
prediction and reasoning tasks. Intuitively, we address the task of generative
knowledge graph construction with code language model: given a code-format
natural language input, the target is to generate triples which can be
represented as code completion tasks. Specifically, we develop schema-aware
prompts that effectively utilize the semantic structure within the knowledge
graph. As code inherently possesses structure, such as class and function
definitions, it serves as a useful model for prior semantic structural
knowledge. Furthermore, we employ a rationale-enhanced generation method to
boost the performance. Rationales provide intermediate steps, thereby improving
knowledge extraction abilities. Experimental results indicate that the proposed
approach can obtain better performance on benchmark datasets compared with
baselines. Code and datasets are available in
https://github.com/zjunlp/DeepKE/tree/main/example/llm.