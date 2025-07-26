---
layout: publication
title: 'BERT And Pals: Projected Attention Layers For Efficient Adaptation In Multi-task
  Learning'
authors: Asa Cooper Stickland, Iain Murray
conference: Arxiv
year: 2019
bibkey: stickland2019bert
citations: 117
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1902.02671'}]
tags: ["Model Architecture", "Training Techniques"]
short_authors: Asa Cooper Stickland, Iain Murray
---
Multi-task learning shares information between related tasks, sometimes
reducing the number of parameters required. State-of-the-art results across
multiple natural language understanding tasks in the GLUE benchmark have
previously used transfer from a single large task: unsupervised pre-training
with BERT, where a separate BERT model was fine-tuned for each task. We explore
multi-task approaches that share a single BERT model with a small number of
additional task-specific parameters. Using new adaptation modules, PALs or
`projected attention layers', we match the performance of separately fine-tuned
models on the GLUE benchmark with roughly 7 times fewer parameters, and obtain
state-of-the-art results on the Recognizing Textual Entailment dataset.