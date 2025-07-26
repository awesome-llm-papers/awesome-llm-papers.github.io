---
layout: publication
title: Block Pruning For Faster Transformers
authors: "Fran\xE7ois Lagunas, Ella Charlaix, Victor Sanh, Alexander M. Rush"
conference: Proceedings of the 2021 Conference on Empirical Methods in Natural Language
  Processing
year: 2021
bibkey: lagunas2021block
citations: 84
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2109.04838'}]
tags: ["Efficiency", "Model Architecture"]
short_authors: Lagunas et al.
---
Pre-training has improved model accuracy for both classification and
generation tasks at the cost of introducing much larger and slower models.
Pruning methods have proven to be an effective way of reducing model size,
whereas distillation methods are proven for speeding up inference. We introduce
a block pruning approach targeting both small and fast models. Our approach
extends structured methods by considering blocks of any size and integrates
this structure into the movement pruning paradigm for fine-tuning. We find that
this approach learns to prune out full components of the underlying model, such
as attention heads. Experiments consider classification and generation tasks,
yielding among other results a pruned model that is a 2.4x faster, 74% smaller
BERT on SQuAD v1, with a 1% drop on F1, competitive both with distilled models
in speed and pruned models in size.