---
layout: publication
title: 'Chemberta-2: Towards Chemical Foundation Models'
authors: Walid Ahmad, Elana Simon, Seyone Chithrananda, Gabriel Grand, Bharath Ramsundar
conference: Arxiv
year: 2022
bibkey: ahmad2022chemberta
citations: 82
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2209.01712'}]
tags: ["Model Architecture"]
short_authors: Ahmad et al.
---
Large pretrained models such as GPT-3 have had tremendous impact on modern
natural language processing by leveraging self-supervised learning to learn
salient representations that can be used to readily finetune on a wide variety
of downstream tasks. We investigate the possibility of transferring such
advances to molecular machine learning by building a chemical foundation model,
ChemBERTa-2, using the language of SMILES. While labeled data for molecular
prediction tasks is typically scarce, libraries of SMILES strings are readily
available. In this work, we build upon ChemBERTa by optimizing the pretraining
process. We compare multi-task and self-supervised pretraining by varying
hyperparameters and pretraining dataset size, up to 77M compounds from PubChem.
To our knowledge, the 77M set constitutes one of the largest datasets used for
molecular pretraining to date. We find that with these pretraining
improvements, we are competitive with existing state-of-the-art architectures
on the MoleculeNet benchmark suite. We analyze the degree to which improvements
in pretraining translate to improvement on downstream tasks.