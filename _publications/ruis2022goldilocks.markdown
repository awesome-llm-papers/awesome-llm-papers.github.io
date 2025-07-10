---
layout: publication
title: 'The Goldilocks Of Pragmatic Understanding: Fine-tuning Strategy Matters For
  Implicature Resolution By Llms'
authors: Laura Ruis et al.
conference: Arxiv
year: 2022
citations: 16
bibkey: ruis2022goldilocks
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2210.14986'}]
tags: [Fine-Tuning, RAG, Reinforcement Learning, Agentic, Training Techniques, Evaluation]
---
Despite widespread use of LLMs as conversational agents, evaluations of
performance fail to capture a crucial aspect of communication: interpreting
language in context -- incorporating its pragmatics. Humans interpret language
using beliefs and prior knowledge about the world. For example, we intuitively
understand the response "I wore gloves" to the question "Did you leave
fingerprints?" as meaning "No". To investigate whether LLMs have the ability to
make this type of inference, known as an implicature, we design a simple task
and evaluate four categories of widely used state-of-the-art models. We find
that, despite only evaluating on utterances that require a binary inference
(yes or no), models in three of these categories perform close to random.
However, LLMs instruction-tuned at the example-level perform significantly
better. These results suggest that certain fine-tuning strategies are far
better at inducing pragmatic understanding in models. We present our findings
as the starting point for further research into evaluating how LLMs interpret
language in context and to drive the development of more pragmatic and useful
models of human discourse.