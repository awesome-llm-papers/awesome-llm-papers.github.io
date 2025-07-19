---
layout: publication
title: Parameter-efficient Fine-tuning With Adapters
authors: Chen Keyu, Pang Yuan, Yang Zi
conference: Proceedings of the 2023 Conference on Empirical Methods in Natural Language
  Processing
year: 2024
bibkey: chen2024parameter
citations: 98
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2405.05493'}]
tags: [Training Techniques, EMNLP, Alt, Prompting, Tools, Evaluation, Efficiency And
    Optimization, Reinforcement Learning, Fine Tuning, Datasets]
---
In the arena of language model fine-tuning, the traditional approaches, such
as Domain-Adaptive Pretraining (DAPT) and Task-Adaptive Pretraining (TAPT),
although effective, but computational intensive. This research introduces a
novel adaptation method utilizing the UniPELT framework as a base and added a
PromptTuning Layer, which significantly reduces the number of trainable
parameters while maintaining competitive performance across various benchmarks.
Our method employs adapters, which enable efficient transfer of pretrained
models to new tasks with minimal retraining of the base model parameters. We
evaluate our approach using three diverse datasets: the GLUE benchmark, a
domain-specific dataset comprising four distinct areas, and the Stanford
Question Answering Dataset 1.1 (SQuAD). Our results demonstrate that our
customized adapter-based method achieves performance comparable to full model
fine-tuning, DAPT+TAPT and UniPELT strategies while requiring fewer or
equivalent amount of parameters. This parameter efficiency not only alleviates
the computational burden but also expedites the adaptation process. The study
underlines the potential of adapters in achieving high performance with
significantly reduced resource consumption, suggesting a promising direction
for future research in parameter-efficient fine-tuning.