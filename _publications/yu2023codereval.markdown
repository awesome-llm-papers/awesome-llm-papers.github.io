---
layout: publication
title: 'Codereval: A Benchmark Of Pragmatic Code Generation With Generative Pre-trained
  Models'
authors: Yu et al.
conference: Proceedings of the IEEE/ACM 46th International Conference on Software
  Engineering
year: 2023
bibkey: yu2023codereval
citations: 56
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2302.00288'}]
tags: [Tools, Training Techniques, Fine Tuning, Evaluation, LLM For Code, LLM for
    Code, RAG, Datasets, Reinforcement Learning]
---
Code generation models based on the pre-training and fine-tuning paradigm
have been increasingly attempted by both academia and industry, resulting in
well-known industrial models such as Codex, CodeGen, and PanGu-Coder. To
evaluate the effectiveness of these models, multiple existing benchmarks are
proposed, including only cases of generating a standalone function, i.e., a
function that may invoke or access only built-in functions and standard
libraries. However, non-standalone functions, which typically are not included
in the existing benchmarks, constitute more than 70% of the functions in
popular open-source projects, and evaluating models' effectiveness on
standalone functions cannot reflect these models' effectiveness on pragmatic
code generation scenarios.
  To help bridge the preceding gap, in this paper, we propose a benchmark named
CoderEval, consisting of 230 Python and 230 Java code generation tasks
carefully curated from popular real-world open-source projects and a
self-contained execution platform to automatically assess the functional
correctness of generated code. CoderEval supports code generation tasks from
six levels of context dependency, where context refers to code elements such as
types, APIs, variables, and consts defined outside the function under
generation but within the dependent third-party libraries, current class, file,
or project. CoderEval can be used to evaluate the effectiveness of models in
generating code beyond only standalone functions. By evaluating three code
generation models on CoderEval, we find that the effectiveness of these models
in generating standalone functions is substantially higher than that in
generating non-standalone functions. Our analysis highlights the current
progress and pinpoints future directions to further improve a model's
effectiveness by leveraging contextual information for pragmatic code
generation.