---
layout: publication
title: Mathematical Reasoning Via Self-supervised Skip-tree Training
authors: Markus N. Rabe, Dennis Lee, Kshitij Bansal, Christian Szegedy
conference: Arxiv
year: 2020
citations: 15
bibkey: rabe2020mathematical
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2006.04757'}]
tags: [Language Modeling, Training Techniques]
---
We examine whether self-supervised language modeling applied to mathematical
formulas enables logical reasoning. We suggest several logical reasoning tasks
that can be used to evaluate language models trained on formal mathematical
statements, such as type inference, suggesting missing assumptions and
completing equalities. To train language models for formal mathematics, we
propose a novel skip-tree task. We find that models trained on the skip-tree
task show surprisingly strong mathematical reasoning abilities, and outperform
models trained on standard skip-sequence tasks. We also analyze the models'
ability to formulate new conjectures by measuring how often the predictions are
provable and useful in other proofs.