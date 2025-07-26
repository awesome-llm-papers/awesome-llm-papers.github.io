---
layout: publication
title: 'From Code To Correctness: Closing The Last Mile Of Code Generation With Hierarchical
  Debugging'
authors: Yuling Shi, Songsong Wang, Chengcheng Wan, Xiaodong Gu
conference: No Venue
year: 2024
bibkey: shi2024code
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/66fe140d7d722f0879868788'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2410.01215'}]
tags: ["Llm For Code"]
short_authors: Shi et al.
---
While large language models have made significant strides in code generation, the pass rate of the generated code is bottlenecked on subtle errors, often requiring human intervention to pass tests, especially for complex problems. Existing LLM-based debugging systems treat generated programs as monolithic units, failing to address bugs at multiple levels of granularity, from low-level syntax errors to high-level algorithmic flaws. In this paper, we introduce Multi-Granularity Debugger (MGDebugger), a hierarchical code debugger by isolating, identifying, and resolving bugs at various levels of granularity. MGDebugger decomposes problematic code into a hierarchical tree structure of subfunctions, with each level representing a particular granularity of error. During debugging, it analyzes each subfunction and iteratively resolves bugs in a bottom-up manner. To effectively test each subfunction, we propose an LLM-simulated Python executor, which traces code execution and tracks important variable states to pinpoint errors accurately. Extensive experiments demonstrate that MGDebugger outperforms existing debugging systems, achieving an 18.9% improvement in accuracy over seed generations in HumanEval and a 97.6% repair success rate in HumanEvalFix. Furthermore, MGDebugger effectively fixes bugs across different categories and difficulty levels, demonstrating its robustness and effectiveness.

https://huggingface.co/discussions/paper/66fe140d7d722f0879868788