---
layout: publication
title: 'DOMINO: A Dual-system For Multi-step Visual Language Reasoning'
authors: Wang et al.
conference: Proceedings of the 57th Annual Meeting of the Association for Computational
  Linguistics
year: 2023
bibkey: wang2023domino
citations: 57
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2310.02804'}]
tags: [Fine Tuning, Training Techniques, ACL, Multimodal Models, Datasets]
---
Visual language reasoning requires a system to extract text or numbers from
information-dense images like charts or plots and perform logical or arithmetic
reasoning to arrive at an answer. To tackle this task, existing work relies on
either (1) an end-to-end vision-language model trained on a large amount of
data, or (2) a two-stage pipeline where a captioning model converts the image
into text that is further read by another large language model to deduce the
answer. However, the former approach forces the model to answer a complex
question with one single step, and the latter approach is prone to inaccurate
or distracting information in the converted text that can confuse the language
model. In this work, we propose a dual-system for multi-step multimodal
reasoning, which consists of a "System-1" step for visual information
extraction and a "System-2" step for deliberate reasoning. Given an input,
System-2 breaks down the question into atomic sub-steps, each guiding System-1
to extract the information required for reasoning from the image. Experiments
on chart and plot datasets show that our method with a pre-trained System-2
module performs competitively compared to prior work on in- and
out-of-distribution data. By fine-tuning the System-2 module (LLaMA-2 70B) on
only a small amount of data on multi-step reasoning, the accuracy of our method
is further improved and surpasses the best fully-supervised end-to-end approach
by 5.7% and a pipeline approach with FlanPaLM (540B) by 7.5% on a challenging
dataset with human-authored questions.