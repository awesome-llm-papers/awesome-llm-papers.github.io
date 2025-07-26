---
layout: publication
title: Parameter-efficient Transfer Learning With Diff Pruning
authors: Demi Guo, Alexander M. Rush, Yoon Kim
conference: 'Proceedings of the 59th Annual Meeting of the Association for Computational
  Linguistics and the 11th International Joint Conference on Natural Language Processing
  (Volume 1: Long Papers)'
year: 2021
bibkey: guo2020parameter
citations: 158
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2012.07463'}]
tags: ["Efficiency", "Fine-Tuning", "Training Techniques"]
short_authors: Demi Guo, Alexander M. Rush, Yoon Kim
---
While task-specific finetuning of pretrained networks has led to significant
empirical advances in NLP, the large size of networks makes finetuning
difficult to deploy in multi-task, memory-constrained settings. We propose diff
pruning as a simple approach to enable parameter-efficient transfer learning
within the pretrain-finetune framework. This approach views finetuning as
learning a task-specific diff vector that is applied on top of the pretrained
parameter vector, which remains fixed and is shared across different tasks. The
diff vector is adaptively pruned during training with a differentiable
approximation to the L0-norm penalty to encourage sparsity. Diff pruning
becomes parameter-efficient as the number of tasks increases, as it requires
storing only the nonzero positions and weights of the diff vector for each
task, while the cost of storing the shared pretrained model remains constant.
It further does not require access to all tasks during training, which makes it
attractive in settings where tasks arrive in stream or the set of tasks is
unknown. We find that models finetuned with diff pruning can match the
performance of fully finetuned baselines on the GLUE benchmark while only
modifying 0.5% of the pretrained model's parameters per task.