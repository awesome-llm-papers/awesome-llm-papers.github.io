---
layout: publication
title: Successive Prompting For Decomposing Complex Questions
authors: Dheeru Dua, Shivanshu Gupta, Sameer Singh, Matt Gardner
conference: Arxiv
year: 2022
citations: 15
bibkey: dua2022successive
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2212.04092'}]
tags: [RAG, Few-Shot, Reinforcement Learning, Prompting]
---
Answering complex questions that require making latent decisions is a
challenging task, especially when limited supervision is available. Recent
works leverage the capabilities of large language models (LMs) to perform
complex question answering in a few-shot setting by demonstrating how to output
intermediate rationalizations while solving the complex question in a single
pass. We introduce ``Successive Prompting'', where we iteratively break down a
complex task into a simple task, solve it, and then repeat the process until we
get the final solution. Successive prompting decouples the supervision for
decomposing complex questions from the supervision for answering simple
questions, allowing us to (1) have multiple opportunities to query in-context
examples at each reasoning step (2) learn question decomposition separately
from question answering, including using synthetic data, and (3) use bespoke
(fine-tuned) components for reasoning steps where a large LM does not perform
well. The intermediate supervision is typically manually written, which can be
expensive to collect. We introduce a way to generate a synthetic dataset which
can be used to bootstrap a model's ability to decompose and answer intermediate
questions. Our best model (with successive prompting) achieves an improvement
of ~5% absolute F1 on a few-shot version of the DROP dataset when compared with
a state-of-the-art model with the same supervision.