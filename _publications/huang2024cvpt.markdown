---
layout: publication
title: 'CVPT: Cross-attention Help Visual Prompt Tuning Adapt Visual Task'
authors: Huang et al.
conference: Lecture Notes in Computer Science
year: 2024
bibkey: huang2024cvpt
citations: 796
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2408.14961'}]
tags: [RAG, Training Techniques, Attention Mechanism, Prompting, Tools, Evaluation,
  Model Architecture, Efficiency And Optimization, Fine Tuning, Datasets]
---
In recent years, the rapid expansion of model sizes has led to large-scale
pre-trained models demonstrating remarkable capabilities. Consequently, there
has been a trend towards increasing the scale of models. However, this trend
introduces significant challenges, including substantial computational costs of
training and transfer to downstream tasks. To address these issues,
Parameter-Efficient Fine-Tuning (PEFT) methods have been introduced. These
methods optimize large-scale pre-trained models for specific tasks by
fine-tuning a select group of parameters. Among these PEFT methods,
adapter-based and prompt-based methods are the primary techniques.
Specifically, in the field of visual fine-tuning, adapters gain prominence over
prompts because of the latter's relatively weaker performance and efficiency.
Under the circumstances, we refine the widely-used Visual Prompt Tuning (VPT)
method, proposing Cross Visual Prompt Tuning (CVPT). CVPT calculates
cross-attention between the prompt tokens and the embedded tokens, which allows
us to compute the semantic relationship between them and conduct the
fine-tuning of models exactly to adapt visual tasks better. Furthermore, we
introduce the weight-sharing mechanism to initialize the parameters of
cross-attention, which avoids massive learnable parameters from cross-attention
and enhances the representative capability of cross-attention. We conduct
comprehensive testing across 25 datasets and the result indicates that CVPT
significantly improves VPT's performance and efficiency in visual tasks. For
example, on the VTAB-1K benchmark, CVPT outperforms VPT over 4% in average
accuracy, rivaling the advanced adapter-based methods in performance and
efficiency. Our experiments confirm that prompt-based methods can achieve
exceptional results in visual fine-tuning.