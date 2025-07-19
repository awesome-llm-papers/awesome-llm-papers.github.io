---
layout: publication
title: Empirical Analysis Of Efficient Fine-tuning Methods For Large Pre-trained Language
  Models
authors: Doering et al.
conference: Nature Machine Intelligence
year: 2024
bibkey: doering2024empirical
citations: 417
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2401.04051'}]
tags: [Security, Ethics And Bias, Training Techniques, Efficiency And Optimization,
  Fine Tuning, Evaluation, LLM for Code, Datasets, Alt]
---
Fine-tuning large pre-trained language models for downstream tasks remains a
critical challenge in natural language processing. This paper presents an
empirical analysis comparing two efficient fine-tuning methods - BitFit and
adapter modules - to standard full model fine-tuning. Experiments conducted on
GLUE benchmark datasets (MRPC, COLA, STS-B) reveal several key insights. The
BitFit approach, which trains only bias terms and task heads, matches full
fine-tuning performance across varying amounts of training data and time
constraints. It demonstrates remarkable stability even with only 30% of data,
outperforming full fine-tuning at intermediate data levels. Adapter modules
exhibit high variability, with inconsistent gains over default models. The
findings indicate BitFit offers an attractive balance between performance and
parameter efficiency. Our work provides valuable perspectives on model tuning,
emphasizing robustness and highlighting BitFit as a promising alternative for
resource-constrained or streaming task settings. The analysis offers actionable
guidelines for efficient adaptation of large pre-trained models, while
illustrating open challenges in stabilizing techniques like adapter modules.