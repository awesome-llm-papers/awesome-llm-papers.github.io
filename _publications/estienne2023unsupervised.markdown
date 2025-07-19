---
layout: publication
title: Unsupervised Calibration Through Prior Adaptation For Text Classification Using
  Large Language Models
authors: Estienne et al.
conference: 'Findings of the Association for Computational Linguistics: EMNLP 2023'
year: 2023
bibkey: estienne2023unsupervised
citations: 75
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2307.06713'}]
tags: [Prompting, Fine Tuning, Training Techniques, ACL, EMNLP]
---
A wide variety of natural language tasks are currently being addressed with
large-scale language models (LLMs). These models are usually trained with a
very large amount of unsupervised text data and adapted to perform a downstream
natural language task using methods like fine-tuning, calibration or in-context
learning. In this work, we propose an approach to adapt the prior class
distribution to perform text classification tasks without the need for labelled
samples and only few in-domain sample queries. The proposed approach treats the
LLM as a black box, adding a stage where the model posteriors are calibrated to
the task. Results show that these methods outperform the un-adapted model for
different number of training shots in the prompt and a previous approach were
calibration is performed without using any adaptation data.