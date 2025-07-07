---
layout: publication
title: 'Qaner: Prompting Question Answering Models For Few-shot Named Entity Recognition'
authors: Andy T. Liu et al.
conference: Arxiv
year: 2022
citations: 22
bibkey: liu2022prompting
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2203.01543'}]
tags: [Efficiency and Optimization, Few-Shot, Security, Prompting]
---
Recently, prompt-based learning for pre-trained language models has succeeded
in few-shot Named Entity Recognition (NER) by exploiting prompts as task
guidance to increase label efficiency. However, previous prompt-based methods
for few-shot NER have limitations such as a higher computational complexity,
poor zero-shot ability, requiring manual prompt engineering, or lack of prompt
robustness. In this work, we address these shortcomings by proposing a new
prompt-based learning NER method with Question Answering (QA), called QaNER.
Our approach includes 1) a refined strategy for converting NER problems into
the QA formulation; 2) NER prompt generation for QA models; 3) prompt-based
tuning with QA models on a few annotated NER examples; 4) zero-shot NER by
prompting the QA model. Comparing the proposed approach with previous methods,
QaNER is faster at inference, insensitive to the prompt quality, and robust to
hyper-parameters, as well as demonstrating significantly better low-resource
performance and zero-shot capability.