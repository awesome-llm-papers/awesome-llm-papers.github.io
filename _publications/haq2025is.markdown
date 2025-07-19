---
layout: publication
title: Is Your LLM Trapped In A Mental Set? Investigative Study On How Mental Sets
  Affect The Reasoning Capabilities Of Llms
authors: Haq et al.
conference: Proceedings of the ACM on Interactive, Mobile, Wearable and Ubiquitous
  Technologies
year: 2025
bibkey: haq2025is
citations: 79
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2501.11833'}]
tags: [Training Techniques, GPT, Evaluation, In Context Learning, Model Architecture,
  Reinforcement Learning, Fine Tuning, Datasets]
---
In this paper, we present an investigative study on how Mental Sets influence
the reasoning capabilities of LLMs. LLMs have excelled in diverse natural
language processing (NLP) tasks, driven by advancements in parameter-efficient
fine-tuning (PEFT) and emergent capabilities like in-context learning (ICL).
For complex reasoning tasks, selecting the right model for PEFT or ICL is
critical, often relying on scores on benchmarks such as MMLU, MATH, and GSM8K.
However, current evaluation methods, based on metrics like F1 Score or
reasoning chain assessments by larger models, overlook a key dimension:
adaptability to unfamiliar situations and overcoming entrenched thinking
patterns. In cognitive psychology, Mental Set refers to the tendency to persist
with previously successful strategies, even when they become inefficient - a
challenge for problem solving and reasoning. We compare the performance of LLM
models like Llama-3.1-8B-Instruct, Llama-3.1-70B-Instruct and GPT-4o in the
presence of mental sets. To the best of our knowledge, this is the first study
to integrate cognitive psychology concepts into the evaluation of LLMs for
complex reasoning tasks, providing deeper insights into their adaptability and
problem-solving efficacy.