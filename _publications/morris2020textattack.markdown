---
layout: publication
title: 'Textattack: A Framework For Adversarial Attacks, Data Augmentation, And Adversarial
  Training In NLP'
authors: Morris et al.
conference: 'Proceedings of the 2020 Conference on Empirical Methods in Natural Language
  Processing: System Demonstrations'
year: 2020
bibkey: morris2020textattack
citations: 220
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2005.05909'}]
tags: [Training Techniques, EMNLP, Tools, BERT, Transformer, Model Architecture, Reinforcement
    Learning, Security, Datasets]
---
While there has been substantial research using adversarial attacks to
analyze NLP models, each attack is implemented in its own code repository. It
remains challenging to develop NLP attacks and utilize them to improve model
performance. This paper introduces TextAttack, a Python framework for
adversarial attacks, data augmentation, and adversarial training in NLP.
TextAttack builds attacks from four components: a goal function, a set of
constraints, a transformation, and a search method. TextAttack's modular design
enables researchers to easily construct attacks from combinations of novel and
existing components. TextAttack provides implementations of 16 adversarial
attacks from the literature and supports a variety of models and datasets,
including BERT and other transformers, and all GLUE tasks. TextAttack also
includes data augmentation and adversarial training modules for using
components of adversarial attacks to improve model accuracy and robustness.
TextAttack is democratizing NLP: anyone can try data augmentation and
adversarial training on any model or dataset, with just a few lines of code.
Code and tutorials are available at https://github.com/QData/TextAttack.