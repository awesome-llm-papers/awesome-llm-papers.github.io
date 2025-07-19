---
layout: publication
title: 'Multipl-e: A Scalable And Extensible Approach To Benchmarking Neural Code
  Generation'
authors: Cassano et al.
conference: IEEE Transactions on Software Engineering
year: 2022
bibkey: cassano2022multipl
citations: 51
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2208.08227'}]
tags: [LLM For Code, Evaluation, LLM for Code, Datasets, Alt]
---
Large language models have demonstrated the ability to generate both natural
language and programming language text. Such models open up the possibility of
multi-language code generation: could code generation models generalize
knowledge from one language to another? Although contemporary code generation
models can generate semantically correct Python code, little is known about
their abilities with other languages. We propose MultiPL-E, a system for
translating unit test-driven code generation benchmarks to new languages. We
create the first massively multilingual code generation benchmark by using
MultiPL-E to translate two popular Python code generation benchmarks to 18
additional programming languages.
  We use MultiPL-E to extend the HumanEval benchmark and MBPP benchmark to 18
languages that encompass a range of programming paradigms and popularity. Using
these new parallel benchmarks, we evaluate the multi-language performance of
three state-of-the-art code generation models: Codex, CodeGen, and InCoder. We
find that Codex matches or even exceeds its performance on Python for several
other languages. The range of programming languages represented in MultiPL-E
allow us to explore the impact of language frequency and language features on
model performance. Finally, the MultiPL-E approach of compiling code generation
benchmarks to new programming languages is both scalable and extensible, making
it straightforward to evaluate new models, benchmarks, and languages.