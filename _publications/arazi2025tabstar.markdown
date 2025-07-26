---
layout: publication
title: 'Tabstar: A Foundation Tabular Model With Semantically Target-aware Representations'
authors: Alan Arazi, Eilam Shapira, Roi Reichart
conference: No Venue
year: 2025
bibkey: arazi2025tabstar
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/6833f8b419852283c4b3bc02'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2505.18125'}]
tags: ["Efficiency", "Model Architecture"]
short_authors: Alan Arazi, Eilam Shapira, Roi Reichart
---
While deep learning has achieved remarkable success across many domains, it has historically underperformed on tabular learning tasks, which remain dominated by gradient boosting decision trees (GBDTs). However, recent advancements are paving the way for Tabular Foundation Models, which can leverage real-world knowledge and generalize across diverse datasets, particularly when the data contains free-text. Although incorporating language model capabilities into tabular tasks has been explored, most existing methods utilize static, target-agnostic textual representations, limiting their effectiveness. We introduce TabSTAR: a Foundation Tabular Model with Semantically Target-Aware Representations. TabSTAR is designed to enable transfer learning on tabular data with textual features, with an architecture free of dataset-specific parameters. It unfreezes a pretrained text encoder and takes as input target tokens, which provide the model with the context needed to learn task-specific embeddings. TabSTAR achieves state-of-the-art performance for both medium- and large-sized datasets across known benchmarks of classification tasks with text features, and its pretraining phase exhibits scaling laws in the number of datasets, offering a pathway for further performance improvements.

https://huggingface.co/discussions/paper/6833f8b419852283c4b3bc02