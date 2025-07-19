---
layout: publication
title: Latent Execution For Neural Program Synthesis
authors: Chen Xinyun, Song Dawn, Tian Yuandong
conference: Proceedings of the 44th International Conference on Software Engineering
year: 2021
bibkey: chen2021latent
citations: 111
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2107.00101'}]
tags: [Training Techniques, LLM For Code, LLM for Code, RAG, Datasets, Reinforcement
    Learning]
---
Program synthesis from input-output (IO) examples has been a long-standing
challenge. While recent works demonstrated limited success on domain-specific
languages (DSL), it remains highly challenging to apply them to real-world
programming languages, such as C. Due to complicated syntax and token
variation, there are three major challenges: (1) unlike many DSLs, programs in
languages like C need to compile first and are not executed via interpreters;
(2) the program search space grows exponentially when the syntax and semantics
of the programming language become more complex; and (3) collecting a
large-scale dataset of real-world programs is non-trivial. As a first step to
address these challenges, we propose LaSynth and show its efficacy in a
restricted-C domain. More specifically, LaSynth learns the latent
representation to approximate the execution of partially generated programs,
even if they are incomplete in syntax (addressing (1)). The learned execution
significantly improves the performance of next token prediction over existing
approaches, facilitating search (addressing (2)). Finally, once trained with
randomly generated ground-truth programs and their IO pairs, LaSynth can
synthesize more concise programs that resemble human-written code. Furthermore,
retraining our model with these synthesized programs yields better performance
with fewer samples for both Karel and C program synthesis, indicating the
promise of leveraging the learned program synthesizer to improve the dataset
quality for input-output program synthesis (addressing (3)). When evaluating on
whether the program execution outputs match the IO pairs, LaSynth achieves
55.2% accuracy on generating simple C code with tens of tokens including loops
and branches, outperforming existing approaches without executors by around
20%.