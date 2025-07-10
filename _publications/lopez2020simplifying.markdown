---
layout: publication
title: Simplifying Paragraph-level Question Generation Via Transformer Language Models
authors: Luis Enrico Lopez, Diane Kathryn Cruz, Jan Christian Blaise Cruz, Charibeth
  Cheng
conference: Lecture Notes in Computer Science
year: 2020
citations: 25
bibkey: lopez2020simplifying
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2005.01107'}]
tags: [Security, Model Architecture, Transformer, RAG, GPT]
---
Question generation (QG) is a natural language generation task where a model
is trained to ask questions corresponding to some input text. Most recent
approaches frame QG as a sequence-to-sequence problem and rely on additional
features and mechanisms to increase performance; however, these often increase
model complexity, and can rely on auxiliary data unavailable in practical use.
A single Transformer-based unidirectional language model leveraging transfer
learning can be used to produce high quality questions while disposing of
additional task-specific complexity. Our QG model, finetuned from GPT-2 Small,
outperforms several paragraph-level QG baselines on the SQuAD dataset by 0.95
METEOR points. Human evaluators rated questions as easy to answer, relevant to
their context paragraph, and corresponding well to natural human speech. Also
introduced is a new set of baseline scores on the RACE dataset, which has not
previously been used for QG tasks. Further experimentation with varying model
capacities and datasets with non-identification type questions is recommended
in order to further verify the robustness of pretrained Transformer-based LMs
as question generators.