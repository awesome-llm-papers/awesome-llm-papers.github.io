---
layout: publication
title: Learning To Prove Theorems Via Interacting With Proof Assistants
authors: Kaiyu Yang, Jia Deng
conference: 2019 IEEE/CVF International Conference on Computer Vision (ICCV)
year: 2019
bibkey: yang2019learning
citations: 94
additional_links: [{name: Code, url: 'https://github.com/princeton-vl/CoqGym'}, {
    name: Paper, url: 'https://arxiv.org/abs/1905.09381'}]
tags: ["ICCV"]
short_authors: Kaiyu Yang, Jia Deng
---
Humans prove theorems by relying on substantial high-level reasoning and
problem-specific insights. Proof assistants offer a formalism that resembles
human mathematical reasoning, representing theorems in higher-order logic and
proofs as high-level tactics. However, human experts have to construct proofs
manually by entering tactics into the proof assistant. In this paper, we study
the problem of using machine learning to automate the interaction with proof
assistants. We construct CoqGym, a large-scale dataset and learning environment
containing 71K human-written proofs from 123 projects developed with the Coq
proof assistant. We develop ASTactic, a deep learning-based model that
generates tactics as programs in the form of abstract syntax trees (ASTs).
Experiments show that ASTactic trained on CoqGym can generate effective tactics
and can be used to prove new theorems not previously provable by automated
methods. Code is available at https://github.com/princeton-vl/CoqGym.