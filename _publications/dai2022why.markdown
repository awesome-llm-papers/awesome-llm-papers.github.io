---
layout: publication
title: Why Can GPT Learn In-context? Language Models Implicitly Perform Gradient Descent
  As Meta-optimizers
authors: Dai et al.
conference: 'Findings of the Association for Computational Linguistics: ACL 2023'
year: 2022
bibkey: dai2022why
citations: 58
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2212.10559'}]
tags: [Model Architecture, Training Techniques, ACL, In Context Learning, Transformer,
  GPT, Reinforcement Learning, Attention Mechanism]
---
Large pretrained language models have shown surprising in-context learning
(ICL) ability. With a few demonstration input-label pairs, they can predict the
label for an unseen input without parameter updates. Despite the great success
in performance, its working mechanism still remains an open question. In this
paper, we explain language models as meta-optimizers and understand in-context
learning as implicit finetuning. Theoretically, we figure out that Transformer
attention has a dual form of gradient descent. On top of it, we understand ICL
as follows: GPT first produces meta-gradients according to the demonstration
examples, and then these meta-gradients are applied to the original GPT to
build an ICL model. We comprehensively compare the behaviors of in-context
learning and explicit finetuning on real tasks to provide empirical evidence
that supports our understanding. Experimental results show that in-context
learning behaves similarly to explicit finetuning from multiple perspectives.
Inspired by the dual form between Transformer attention and gradient descent,
we design a momentum-based attention by analogy with gradient descent with
momentum. The improved performance over vanilla attention further supports our
understanding from another perspective, and more importantly, shows the
potential to utilize our understanding for future model design. The code is
available at https://aka.ms/icl.