---
layout: publication
title: 'Classeval: A Manually-crafted Benchmark For Evaluating Llms On Class-level
  Code Generation'
authors: Xueying Du et al.
conference: Arxiv
year: 2023
citations: 15
bibkey: du2023manually
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2308.01861'}, {name: Code,
    url: 'https://github.com/FudanSELab/ClassEval'}]
tags: [Has Code, GPT, Model Architecture]
---
In this work, we make the first attempt to evaluate LLMs in a more
challenging code generation scenario, i.e. class-level code generation. We
first manually construct the first class-level code generation benchmark
ClassEval of 100 class-level Python code generation tasks with approximately
500 person-hours. Based on it, we then perform the first study of 11
state-of-the-art LLMs on class-level code generation. Based on our results, we
have the following main findings. First, we find that all existing LLMs show
much worse performance on class-level code generation compared to on standalone
method-level code generation benchmarks like HumanEval; and the method-level
coding ability cannot equivalently reflect the class-level coding ability among
LLMs. Second, we find that GPT-4 and GPT-3.5 still exhibit dominate superior
than other LLMs on class-level code generation, and the second-tier models
includes Instruct-Starcoder, Instruct-Codegen, and Wizardcoder with very
similar performance. Third, we find that generating the entire class all at
once (i.e. holistic generation strategy) is the best generation strategy only
for GPT-4 and GPT-3.5, while method-by-method generation (i.e. incremental and
compositional) is better strategies for the other models with limited ability
of understanding long instructions and utilizing the middle information.
Lastly, we find the limited model ability of generating method-dependent code
and discuss the frequent error types in generated classes. Our benchmark is
available at https://github.com/FudanSELab/ClassEval.