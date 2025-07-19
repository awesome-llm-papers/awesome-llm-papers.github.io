---
layout: publication
title: 'Rustmap: Towards Project-scale C-to-rust Migration Via Program Analysis And
  LLM'
authors: Cai et al.
conference: 'Findings of the Association for Computational Linguistics: EMNLP 2023'
year: 2025
bibkey: cai2025rustmap
citations: 92
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2503.17741'}]
tags: [Model Architecture, Tools, LLM For Code, ACL, EMNLP, GPT, Reinforcement Learning,
  Responsible AI]
---
Migrating existing C programs into Rust is increasingly desired, as Rust
offers superior memory safety while maintaining C's high performance. However,
vastly different features between C and Rust--e.g., distinct definitions and
usages of pointers and references--pose significant challenges beyond mere
syntactic translation. Existing automated translation tools, such as C2Rust,
may rely too much on syntactic, template-based translation and generate unsafe
Rust code that is hard for human developers to read, maintain, or even compile.
More semantic-aware translation that produces safer, idiomatic, and runnable
Rust code is much needed. This paper introduces a novel dependency-guided and
large language model (LLM)-based C-to-Rust translation approach, RustMap, based
on three key ideas: (1) Utilize LLM capabilities to produce idiomatic Rust code
from given small pieces of C code, (2) Mitigate LLM limitations in handling
large codebases by breaking project-scale C programs into smaller units for
translation according to their usage dependencies and composing them into a
runnable Rust program, and (3) Enhance the correctness of the translated Rust
program by using test cases to check input/output equivalence, isolate faulty
code when execution states deviate, and iteratively refine the translation
using feedback from compilation and test errors. We empirically evaluate
RustMap on 126 real-world programs, including 125 from Rosetta Code and a 7000+
line bzip2 implementation using GPT-4o as the LLM. RustMap shows promising
results, guiding GPT-4o to produce idiomatic, readable, and functional Rust
code with significantly less unsafe code than other tools, and revealing
non-trivial translation patterns reusable for future research.