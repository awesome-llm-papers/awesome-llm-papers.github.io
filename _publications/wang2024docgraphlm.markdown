---
layout: publication
title: 'Docgraphlm: Documental Graph Language Model For Information Extraction'
authors: Dongsheng Wang, Zhiqiang Ma, Armineh Nourbakhsh, Kang Gu, Sameena Shah
conference: No Venue
year: 2024
bibkey: wang2024docgraphlm
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/659b6ac6eff07dcf1ff16a2d'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2401.02823'}]
tags: ["Datasets", "Model Architecture", "Training Techniques"]
short_authors: Wang et al.
---
Advances in Visually Rich Document Understanding (VrDU) have enabled information extraction and question answering over documents with complex layouts. Two tropes of architectures have emerged -- transformer-based models inspired by LLMs, and Graph Neural Networks. In this paper, we introduce DocGraphLM, a novel framework that combines pre-trained language models with graph semantics. To achieve this, we propose 1) a joint encoder architecture to represent documents, and 2) a novel link prediction approach to reconstruct document graphs. DocGraphLM predicts both directions and distances between nodes using a convergent joint loss function that prioritizes neighborhood restoration and downweighs distant node detection. Our experiments on three SotA datasets show consistent improvement on IE and QA tasks with the adoption of graph features. Moreover, we report that adopting the graph features accelerates convergence in the learning process during training, despite being solely constructed through link prediction.

https://huggingface.co/discussions/paper/659b6ac6eff07dcf1ff16a2d