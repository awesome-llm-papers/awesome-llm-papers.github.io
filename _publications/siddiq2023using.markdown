---
layout: publication
title: 'Using Large Language Models To Generate Junit Tests: An Empirical Study'
authors: Mohammed Latif Siddiq et al.
conference: 'EASE 2024: 28th International Conference on Evaluation and Assessment
  in Software Engineering'
year: 2023
citations: 35
bibkey: siddiq2023using
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2305.00418'}]
tags: [Language Modeling, Model Architecture, GPT, Fine-Tuning, RAG, Prompting, Training
    Techniques, Evaluation]
---
A code generation model generates code by taking a prompt from a code
comment, existing code, or a combination of both. Although code generation
models (e.g., GitHub Copilot) are increasingly being adopted in practice, it is
unclear whether they can successfully be used for unit test generation without
fine-tuning for a strongly typed language like Java. To fill this gap, we
investigated how well three models (Codex, GPT-3.5-Turbo, and StarCoder) can
generate unit tests. We used two benchmarks (HumanEval and Evosuite SF110) to
investigate the effect of context generation on the unit test generation
process. We evaluated the models based on compilation rates, test correctness,
test coverage, and test smells. We found that the Codex model achieved above
80% coverage for the HumanEval dataset, but no model had more than 2% coverage
for the EvoSuite SF110 benchmark. The generated tests also suffered from test
smells, such as Duplicated Asserts and Empty Tests.