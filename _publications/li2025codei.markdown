---
layout: publication
title: 'Codei/o: Condensing Reasoning Patterns Via Code Input-output Prediction'
authors: Junlong Li, Daya Guo, Dejian Yang, Runxin Xu, Yu Wu, Junxian He
conference: No Venue
year: 2025
bibkey: li2025codei
additional_links: [{name: Code, url: 'https://github.com/hkust-nlp/CodeIO'}, {name: Code,
    url: 'https://huggingface.co/discussions/paper/67ac0ab820e98bddc5c1a039'}, {name: Paper,
    url: 'https://arxiv.org/abs/hf2502.07316'}]
tags: ["Has Code", "Llm For Code"]
short_authors: Li et al.
---
Reasoning is a fundamental capability of Large Language Models. While prior research predominantly focuses on enhancing narrow skills like math or code generation, improving performance on many other reasoning tasks remains challenging due to sparse and fragmented training data. To address this issue, we propose CodeI/O, a novel approach that systematically condenses diverse reasoning patterns inherently embedded in contextually-grounded codes, through transforming the original code into a code input-output prediction format. By training models to predict inputs/outputs given code and test cases entirely in natural language as Chain-of-Thought (CoT) rationales, we expose them to universal reasoning primitives -- like logic flow planning, state-space searching, decision tree traversal, and modular decomposition -- while decoupling structured reasoning from code-specific syntax and preserving procedural rigor. Experimental results demonstrate CodeI/O leads to consistent improvements across symbolic, scientific, logic, math & numerical, and commonsense reasoning tasks. By matching the existing ground-truth outputs or re-executing the code with predicted inputs, we can verify each prediction and further enhance the CoTs through multi-turn revision, resulting in CodeI/O++ and achieving higher performance. Our data and models are available at https://github.com/hkust-nlp/CodeIO.

https://huggingface.co/discussions/paper/67ac0ab820e98bddc5c1a039