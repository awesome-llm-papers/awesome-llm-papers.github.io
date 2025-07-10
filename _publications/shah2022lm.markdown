---
layout: publication
title: 'Lm-nav: Robotic Navigation With Large Pre-trained Models Of Language, Vision,
  And Action'
authors: Dhruv Shah, Blazej Osinski, Brian Ichter, Sergey Levine
conference: Arxiv
year: 2022
citations: 36
bibkey: shah2022lm
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2207.04429'}, {name: Code,
    url: 'https://sites.google.com/view/lmnav'}]
tags: [Language Modeling, Has Code, Model Architecture, GPT, Fine-Tuning, Reinforcement
    Learning, Training Techniques]
---
Goal-conditioned policies for robotic navigation can be trained on large,
unannotated datasets, providing for good generalization to real-world settings.
However, particularly in vision-based settings where specifying goals requires
an image, this makes for an unnatural interface. Language provides a more
convenient modality for communication with robots, but contemporary methods
typically require expensive supervision, in the form of trajectories annotated
with language descriptions. We present a system, LM-Nav, for robotic navigation
that enjoys the benefits of training on unannotated large datasets of
trajectories, while still providing a high-level interface to the user. Instead
of utilizing a labeled instruction following dataset, we show that such a
system can be constructed entirely out of pre-trained models for navigation
(ViNG), image-language association (CLIP), and language modeling (GPT-3),
without requiring any fine-tuning or language-annotated robot data. We
instantiate LM-Nav on a real-world mobile robot and demonstrate long-horizon
navigation through complex, outdoor environments from natural language
instructions. For videos of our experiments, code release, and an interactive
Colab notebook that runs in your browser, please check out our project page
https://sites.google.com/view/lmnav