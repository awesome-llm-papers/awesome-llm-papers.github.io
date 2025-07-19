---
layout: publication
title: Meta Module Network For Compositional Visual Reasoning
authors: Chen et al.
conference: 2021 IEEE Winter Conference on Applications of Computer Vision (WACV)
year: 2019
bibkey: chen2019meta
citations: 56
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1910.03230'}]
tags: [Interpretability And Explainability, Model Architecture, Datasets, Applications]
---
Neural Module Network (NMN) exhibits strong interpretability and
compositionality thanks to its handcrafted neural modules with explicit
multi-hop reasoning capability. However, most NMNs suffer from two critical
drawbacks: 1) scalability: customized module for specific function renders it
impractical when scaling up to a larger set of functions in complex tasks; 2)
generalizability: rigid pre-defined module inventory makes it difficult to
generalize to unseen functions in new tasks/domains. To design a more powerful
NMN architecture for practical use, we propose Meta Module Network (MMN)
centered on a novel meta module, which can take in function recipes and morph
into diverse instance modules dynamically. The instance modules are then woven
into an execution graph for complex visual reasoning, inheriting the strong
explainability and compositionality of NMN. With such a flexible instantiation
mechanism, the parameters of instance modules are inherited from the central
meta module, retaining the same model complexity as the function set grows,
which promises better scalability. Meanwhile, as functions are encoded into the
embedding space, unseen functions can be readily represented based on its
structural similarity with previously observed ones, which ensures better
generalizability. Experiments on GQA and CLEVR datasets validate the
superiority of MMN over state-of-the-art NMN designs. Synthetic experiments on
held-out unseen functions from GQA dataset also demonstrate the strong
generalizability of MMN. Our code and model are released in Github
https://github.com/wenhuchen/Meta-Module-Network.