---
layout: publication
title: Benchmarking LLM Code Generation For Audio Programming With Visual Dataflow
  Languages
authors: William Zhang, Maria Leon, Ryan Xu, Adrian Cardenas, Amelia Wissink, Hanna
  Martin, Maya Srikanth, Kaya Dorogi, Christian Valadez, Pedro Perez, Citlalli Grijalva,
  Corey Zhang, Mark Santolucito
conference: Transactions of the Association for Computational Linguistics
year: 2024
bibkey: zhang2024benchmarking
citations: 130
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2409.00856'}]
tags: ["Evaluation", "Llm For Code", "TACL"]
short_authors: Zhang et al.
---
Node-based programming languages are increasingly popular in media arts
coding domains. These languages are designed to be accessible to users with
limited coding experience, allowing them to achieve creative output without an
extensive programming background. Using LLM-based code generation to further
lower the barrier to creative output is an exciting opportunity. However, the
best strategy for code generation for visual node-based programming languages
is still an open question. In particular, such languages have multiple levels
of representation in text, each of which may be used for code generation. In
this work, we explore the performance of LLM code generation in audio
programming tasks in visual programming languages at multiple levels of
representation. We explore code generation through metaprogramming code
representations for these languages (i.e., coding the language using a
different high-level text-based programming language), as well as through
direct node generation with JSON. We evaluate code generated in this way for
two visual languages for audio programming on a benchmark set of coding
problems. We measure both correctness and complexity of the generated code. We
find that metaprogramming results in more semantically correct generated code,
given that the code is well-formed (i.e., is syntactically correct and runs).
We also find that prompting for richer metaprogramming using randomness and
loops led to more complex code.