---
layout: publication
title: 'Systematic Generalization: What Is Required And Can It Be Learned?'
authors: Dzmitry Bahdanau, Shikhar Murty, Michael Noukhovitch, Thien Huu Nguyen, Harm
  de Vries, Aaron Courville
conference: Arxiv
year: 2018
bibkey: bahdanau2018systematic
citations: 78
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1811.12889'}]
tags: ["Training Techniques"]
short_authors: Bahdanau et al.
---
Numerous models for grounded language understanding have been recently
proposed, including (i) generic models that can be easily adapted to any given
task and (ii) intuitively appealing modular models that require background
knowledge to be instantiated. We compare both types of models in how much they
lend themselves to a particular form of systematic generalization. Using a
synthetic VQA test, we evaluate which models are capable of reasoning about all
possible object pairs after training on only a small subset of them. Our
findings show that the generalization of modular models is much more systematic
and that it is highly sensitive to the module layout, i.e. to how exactly the
modules are connected. We furthermore investigate if modular models that
generalize well could be made more end-to-end by learning their layout and
parametrization. We find that end-to-end methods from prior work often learn
inappropriate layouts or parametrizations that do not facilitate systematic
generalization. Our results suggest that, in addition to modularity, systematic
generalization in language understanding may require explicit regularizers or
priors.