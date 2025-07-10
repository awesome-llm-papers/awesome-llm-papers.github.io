---
layout: publication
title: 'Coregen: Contextualized Code Representation Learning For Commit Message Generation'
authors: Lun Yiu Nie et al.
conference: Neurocomputing
year: 2020
citations: 38
bibkey: nie2020contextualized
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2007.06934'}]
tags: [Model Architecture, Transformer, Tools, Reinforcement Learning, Training Techniques,
  Evaluation]
---
Automatic generation of high-quality commit messages for code commits can
substantially facilitate software developers' works and coordination. However,
the semantic gap between source code and natural language poses a major
challenge for the task. Several studies have been proposed to alleviate the
challenge but none explicitly involves code contextual information during
commit message generation. Specifically, existing research adopts static
embedding for code tokens, which maps a token to the same vector regardless of
its context. In this paper, we propose a novel Contextualized code
representation learning strategy for commit message Generation (CoreGen).
CoreGen first learns contextualized code representations which exploit the
contextual information behind code commit sequences. The learned
representations of code commits built upon Transformer are then fine-tuned for
downstream commit message generation. Experiments on the benchmark dataset
demonstrate the superior effectiveness of our model over the baseline models
with at least 28.18% improvement in terms of BLEU-4 score. Furthermore, we also
highlight the future opportunities in training contextualized code
representations on larger code corpus as a solution to low-resource tasks and
adapting the contextualized code representation framework to other code-to-text
generation tasks.