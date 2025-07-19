---
layout: publication
title: 'Relational Schemata In BERT Are Inducible, Not Emergent: A Study Of Performance
  Vs. Competence In Language Models'
authors: Gawin Cole
conference: Human Communication Research
year: 2025
bibkey: gawin2025relational
citations: 72
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2506.11485'}]
tags: [Training Techniques, Ethics And Bias, BERT, Model Architecture, Fine Tuning]
---
While large language models like BERT demonstrate strong empirical performance on semantic tasks, whether this reflects true conceptual competence or surface-level statistical association remains unclear. I investigate whether BERT encodes abstract relational schemata by examining internal representations of concept pairs across taxonomic, mereological, and functional relations. I compare BERT's relational classification performance with representational structure in [CLS] token embeddings. Results reveal that pretrained BERT enables high classification accuracy, indicating latent relational signals. However, concept pairs organize by relation type in high-dimensional embedding space only after fine-tuning on supervised relation classification tasks. This indicates relational schemata are not emergent from pretraining alone but can be induced via task scaffolding. These findings demonstrate that behavioral performance does not necessarily imply structured conceptual understanding, though models can acquire inductive biases for grounded relational abstraction through appropriate training.