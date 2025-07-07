---
layout: publication
title: Interactive Code Generation Via Test-driven User-intent Formalization
authors: Shuvendu K. Lahiri et al.
conference: Arxiv
year: 2022
citations: 17
bibkey: lahiri2022interactive
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2208.05950'}]
tags: [RAG, Efficiency and Optimization, Pruning]
---
Large language models (LLMs) have shown great potential in automating
significant aspects of coding by producing natural code from informal natural
language (NL) intent. However, when interacting with LLMs, users have no
guarantees that the code suggestions produced correctly satisfy the intent they
provided. In fact, it is hard to define a notion of correctness since natural
language can be ambiguous and lacks a formal semantics.
  In this paper, we propose the workflow of \{\it interactive test-driven code
generation\}, which leverages lightweight user feedback to (a) formalize the
user intent using generated tests that can be useful for debugging, and (b)
produce an improved set of code suggestions by pruning and ranking candidate
code suggestions. We describe a language-agnostic abstract algorithm and a
concrete implementation TiCoder. We perform an automated evaluation of TiCoder
on the *MBPP* and *HumanEval* code generation benchmarks. Our results
are promising with using the OpenAI Codex LLM: our best algorithm improves the
\passk\{1\} code generation accuracy (in absolute percentages) between \\(22.49%\\)
to \\(37.71%\\) for MBPP and between \\(24.79%\\) to \\(53.98%\\) for HumanEval using
between 1 to 5 simulated user queries.