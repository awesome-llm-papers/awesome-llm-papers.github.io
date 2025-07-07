---
layout: publication
title: 'ATTEMPT: Parameter-efficient Multi-task Tuning Via Attentional Mixtures Of
  Soft Prompts'
authors: Akari Asai, Mohammadreza Salehi, Matthew E. Peters, Hannaneh Hajishirzi
conference: Arxiv
year: 2022
citations: 20
bibkey: asai2022parameter
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2205.11961'}]
tags: [Training Techniques, Few-Shot, Attention Mechanism, Fine-Tuning, Prompting,
  Model Architecture]
---
This work introduces a new multi-task, parameter-efficient language model
(LM) tuning method that learns to transfer knowledge across different tasks via
a mixture of soft prompts-small prefix embedding vectors pre-trained for
different tasks. Our method, called ATTEMPT (ATTEntional Mixtures of Prompt
Tuning), obtains source prompts as encodings of large-scale source tasks into a
small number of parameters and trains an attention module to interpolate the
source prompts and a newly initialized target prompt for every instance in the
target task. During training, only the target task prompt and the attention
weights, which are shared between tasks in multi-task training, are updated,
while the original LM and source prompts are intact. ATTEMPT is highly
parameter-efficient (e.g., updates 2,300 times fewer parameters than full
fine-tuning) while achieving high task performance using knowledge from
high-resource tasks. Moreover, it is modular using pre-trained soft prompts,
and can flexibly add or remove source prompts for effective knowledge transfer.
Our experimental results across 21 diverse NLP datasets show that ATTEMPT
significantly outperforms prompt tuning and outperforms or matches fully
fine-tuned or other parameter-efficient tuning approaches that use over ten
times more parameters. Finally, ATTEMPT outperforms previous work in few-shot
learning settings.