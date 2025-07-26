---
layout: publication
title: Specialized Language Models With Cheap Inference From Limited Domain Data
authors: David Grangier, Angelos Katharopoulos, Pierre Ablin, Awni Hannun
conference: No Venue
year: 2024
bibkey: grangier2024specialized
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2402.01093'}]
tags: ["Datasets", "Model Architecture", "Training Techniques"]
short_authors: Grangier et al.
---
Large language models have emerged as a versatile tool but are challenging to apply to tasks lacking large inference budgets and large in-domain training sets. This work formalizes these constraints and distinguishes four important variables: the pretraining budget (for training before the target domain is known), the specialization budget (for training after the target domain is known), the inference budget, and the in-domain training set size. Across these settings, we compare different approaches from the machine learning literature. Limited by inference cost, we find better alternatives to the standard practice of training very large vanilla transformer models. In particular, we show that hyper-networks and mixture of experts have better perplexity for large pretraining budgets, while small models trained on importance sampled datasets are attractive for large specialization budgets.

https://huggingface.co/discussions/paper/65c04b5fef796a0c7f6b3348