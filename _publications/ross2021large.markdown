---
layout: publication
title: Large-scale Chemical Language Representations Capture Molecular Structure And
  Properties
authors: Ross et al.
conference: Nature Machine Intelligence
year: 2021
bibkey: ross2021large
citations: 211
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2106.09553'}]
tags: [Model Architecture, Training Techniques, Evaluation, LLM for Code, Transformer,
  RAG, Datasets, Attention Mechanism, Large Scale Training]
---
Models based on machine learning can enable accurate and fast molecular
property predictions, which is of interest in drug discovery and material
design. Various supervised machine learning models have demonstrated promising
performance, but the vast chemical space and the limited availability of
property labels make supervised learning challenging. Recently, unsupervised
transformer-based language models pretrained on a large unlabelled corpus have
produced state-of-the-art results in many downstream natural language
processing tasks. Inspired by this development, we present molecular embeddings
obtained by training an efficient transformer encoder model, MoLFormer, which
uses rotary positional embeddings. This model employs a linear attention
mechanism, coupled with highly distributed training, on SMILES sequences of 1.1
billion unlabelled molecules from the PubChem and ZINC datasets. We show that
the learned molecular representation outperforms existing baselines, including
supervised and self-supervised graph neural networks and language models, on
several downstream tasks from ten benchmark datasets. They perform
competitively on two others. Further analyses, specifically through the lens of
attention, demonstrate that MoLFormer trained on chemical SMILES indeed learns
the spatial relationships between atoms within a molecule. These results
provide encouraging evidence that large-scale molecular language models can
capture sufficient chemical and structural information to predict various
distinct molecular properties, including quantum-chemical properties.