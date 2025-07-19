---
layout: publication
title: Code Translation With Compiler Representations
authors: Szafraniec et al.
conference: Proceedings of the 29th International Conference on Compiler Construction
year: 2022
bibkey: szafraniec2022code
citations: 51
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2207.03578'}]
tags: [RAG, Evaluation, LLM For Code]
---
In this paper, we leverage low-level compiler intermediate representations
(IR) to improve code translation. Traditional transpilers rely on syntactic
information and handcrafted rules, which limits their applicability and
produces unnatural-looking code. Applying neural machine translation (NMT)
approaches to code has successfully broadened the set of programs on which one
can get a natural-looking translation. However, they treat the code as
sequences of text tokens, and still do not differentiate well enough between
similar pieces of code which have different semantics in different languages.
The consequence is low quality translation, reducing the practicality of NMT,
and stressing the need for an approach significantly increasing its accuracy.
Here we propose to augment code translation with IRs, specifically LLVM IR,
with results on the C++, Java, Rust, and Go languages. Our method improves upon
the state of the art for unsupervised code translation, increasing the number
of correct translations by 11% on average, and up to 79% for the Java -> Rust
pair with greedy decoding. We extend previous test sets for code translation,
by adding hundreds of Go and Rust functions. Additionally, we train models with
high performance on the problem of IR decompilation, generating programming
source code from IR, and study using IRs as intermediary pivot for translation.