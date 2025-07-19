---
layout: publication
title: 'TIMER: Temporal Instruction Modeling And Evaluation For Longitudinal Clinical
  Records'
authors: Cui et al.
conference: Proceedings of the 21th ACM SIGKDD International Conference on Knowledge
  Discovery and Data Mining
year: 2025
bibkey: cui2025timer
citations: 107
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2503.04176'}]
tags: [Alt, Tools, Evaluation, Fine Tuning, Datasets, KDD]
---
Large language models (LLMs) have emerged as promising tools for assisting in
medical tasks, yet processing Electronic Health Records (EHRs) presents unique
challenges due to their longitudinal nature. While LLMs' capabilities to
perform medical tasks continue to improve, their ability to reason over
temporal dependencies across multiple patient visits and time frames remains
unexplored. We introduce TIMER (Temporal Instruction Modeling and Evaluation
for Longitudinal Clinical Records), a framework that incorporate
instruction-response pairs grounding to different parts of a patient's record
as a critical dimension in both instruction evaluation and tuning for
longitudinal clinical records. We develop TIMER-Bench, the first time-aware
benchmark that evaluates temporal reasoning capabilities over longitudinal
EHRs, as well as TIMER-Instruct, an instruction-tuning methodology for LLMs to
learn reasoning over time. We demonstrate that models fine-tuned with
TIMER-Instruct improve performance by 7.3% on human-generated benchmarks and
9.2% on TIMER-Bench, indicating that temporal instruction-tuning improves model
performance for reasoning over EHR.