---
layout: publication
title: Teaching Autoregressive Language Models Complex Tasks By Demonstration
authors: Recchia Gabriel
conference: Arxiv
year: 2021
bibkey: recchia2021teaching
citations: 55
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2109.02102'}]
tags: [Training Techniques, GPT, Transformer, Model Architecture, Fine Tuning, Datasets]
---
This paper demonstrates that by fine-tuning an autoregressive language model
(GPT-Neo) on appropriately structured step-by-step demonstrations, it is
possible to teach it to execute a mathematical task that has previously proved
difficult for Transformers - longhand modulo operations - with a relatively
small number of examples. Specifically, we fine-tune GPT-Neo to solve the
numbers__div_remainder task from the DeepMind Mathematics Dataset; Saxton et
al. (arXiv:1904.01557) reported below 40% accuracy on this task with 2 million
training examples. We show that after fine-tuning on 200 appropriately
structured demonstrations of solving long division problems and reporting the
remainders, the smallest available GPT-Neo model achieves over 80% accuracy.
This is achieved by constructing an appropriate dataset for fine-tuning, with
no changes to the learning algorithm. These results suggest that fine-tuning
autoregressive language models on small sets of well-crafted demonstrations may
be a useful paradigm for enabling individuals without training in machine
learning to coax such models to perform some kinds of complex multi-step tasks.