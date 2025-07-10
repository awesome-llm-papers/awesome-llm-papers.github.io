---
layout: publication
title: Evaluating Correctness And Faithfulness Of Instruction-following Models For
  Question Answering
authors: Vaibhav Adlakha, Parishad Behnamghader, Xing Han Lu, Nicholas Meade, Siva
  Reddy
conference: Transactions of the Association for Computational Linguistics
year: 2023
citations: 23
bibkey: adlakha2023evaluating
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2307.16877'}, {name: Code,
    url: 'https://github.com/McGill-NLP/instruct-qa'}]
tags: [Has Code, Fine-Tuning, RAG, Reinforcement Learning, Training Techniques, Evaluation]
---
Retriever-augmented instruction-following models are attractive alternatives
to fine-tuned approaches for information-seeking tasks such as question
answering (QA). By simply prepending retrieved documents in its input along
with an instruction, these models can be adapted to various information domains
and tasks without additional fine-tuning. While the model responses tend to be
natural and fluent, the additional verbosity makes traditional QA evaluation
metrics such as exact match (EM) and F1 unreliable for accurately quantifying
model performance.
  In this work, we investigate the performance of instruction-following models
across three information-seeking QA tasks. We use both automatic and human
evaluation to evaluate these models along two dimensions: 1) how well they
satisfy the user's information need (correctness), and 2) whether they produce
a response based on the provided knowledge (faithfulness). Guided by human
evaluation and analysis, we highlight the shortcomings of traditional metrics
for both correctness and faithfulness. We then propose simple token-overlap
based and model-based metrics that reflect the true performance of these
models. Our analysis reveals that instruction-following models are competitive,
and sometimes even outperform fine-tuned models for correctness. However, these
models struggle to stick to the provided knowledge and often hallucinate in
their responses. We hope our work encourages a more holistic evaluation of
instruction-following models for QA. Our code and data is available at
https://github.com/McGill-NLP/instruct-qa