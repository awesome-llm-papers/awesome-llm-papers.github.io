---
layout: publication
title: 'Instructionner: A Multi-task Instruction-based Generative Framework For Few-shot
  NER'
authors: Liwen Wang et al.
conference: Arxiv
year: 2022
citations: 25
bibkey: wang2022multi
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2203.03903'}]
tags: [Fine-Tuning, Few-Shot, Tools, Prompting, Pre-Training, Training Techniques]
---
Recently, prompt-based methods have achieved significant performance in
few-shot learning scenarios by bridging the gap between language model
pre-training and fine-tuning for downstream tasks. However, existing prompt
templates are mostly designed for sentence-level tasks and are inappropriate
for sequence labeling objectives. To address the above issue, we propose a
multi-task instruction-based generative framework, named InstructionNER, for
low-resource named entity recognition. Specifically, we reformulate the NER
task as a generation problem, which enriches source sentences with
task-specific instructions and answer options, then inferences the entities and
types in natural language. We further propose two auxiliary tasks, including
entity extraction and entity typing, which enable the model to capture more
boundary information of entities and deepen the understanding of entity type
semantics, respectively. Experimental results show that our method consistently
outperforms other baselines on five datasets in few-shot settings.