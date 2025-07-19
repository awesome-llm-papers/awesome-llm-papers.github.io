---
layout: publication
title: Toward Machine-guided, Human-initiated Explanatory Interactive Learning
authors: Popordanoska Teodora, Kumar Mohit, Teso Stefano
conference: Proceedings of the 2019 AAAI/ACM Conference on AI, Ethics, and Society
year: 2020
bibkey: popordanoska2020toward
citations: 108
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2007.10018'}]
tags: [Interpretability And Explainability, Evaluation, Ethics And Bias, AAAI, Responsible
    AI]
---
Recent work has demonstrated the promise of combining local explanations with
active learning for understanding and supervising black-box models. Here we
show that, under specific conditions, these algorithms may misrepresent the
quality of the model being learned. The reason is that the machine illustrates
its beliefs by predicting and explaining the labels of the query instances: if
the machine is unaware of its own mistakes, it may end up choosing queries on
which it performs artificially well. This biases the "narrative" presented by
the machine to the user.We address this narrative bias by introducing
explanatory guided learning, a novel interactive learning strategy in which: i)
the supervisor is in charge of choosing the query instances, while ii) the
machine uses global explanations to illustrate its overall behavior and to
guide the supervisor toward choosing challenging, informative instances. This
strategy retains the key advantages of explanatory interaction while avoiding
narrative bias and compares favorably to active learning in terms of sample
complexity. An initial empirical evaluation with a clustering-based prototype
highlights the promise of our approach.