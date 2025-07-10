---
layout: publication
title: 'GODEL: Large-scale Pre-training For Goal-directed Dialog'
authors: Baolin Peng et al.
conference: Arxiv
year: 2022
citations: 28
bibkey: peng2022large
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2206.11309'}]
tags: [Model Architecture, GPT, Fine-Tuning, RAG, Few-Shot, Reinforcement Learning,
  Pre-Training, Training Techniques, Evaluation]
---
We introduce GODEL (Grounded Open Dialogue Language Model), a large
pre-trained language model for dialog. In contrast with earlier models such as
DialoGPT, GODEL leverages a new phase of grounded pre-training designed to
better support adapting GODEL to a wide range of downstream dialog tasks that
require information external to the current conversation (e.g., a database or
document) to produce good responses. Experiments against an array of benchmarks
that encompass task-oriented dialog, conversational QA, and grounded
open-domain dialog show that GODEL outperforms state-of-the-art pre-trained
dialog models in few-shot fine-tuning setups, in terms of both human and
automatic evaluation. A novel feature of our evaluation methodology is the
introduction of a notion of utility that assesses the usefulness of responses
(extrinsic evaluation) in addition to their communicative features (intrinsic
evaluation). We show that extrinsic evaluation offers improved inter-annotator
agreement and correlation with automated metrics. Code and data processing
scripts are publicly available.