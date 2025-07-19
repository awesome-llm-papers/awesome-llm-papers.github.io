---
layout: publication
title: 'Tx-ray: Quantifying And Explaining Model-knowledge Transfer In (un-)supervised
  NLP'
authors: Rethmeier Nils, Saxena Vageesh Kumar, Augenstein Isabelle
conference: 2020 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2019
bibkey: rethmeier2019tx
citations: 78
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1912.00982'}]
tags: [Interpretability And Explainability, Training Techniques, CVPR, Evaluation,
  Efficiency And Optimization, Reinforcement Learning, Fine Tuning, Pruning]
---
While state-of-the-art NLP explainability (XAI) methods focus on explaining
per-sample decisions in supervised end or probing tasks, this is insufficient
to explain and quantify model knowledge transfer during (un-)supervised
training. Thus, for TX-Ray, we modify the established computer vision
explainability principle of 'visualizing preferred inputs of neurons' to make
it usable transfer analysis and NLP. This allows one to analyze, track and
quantify how self- or supervised NLP models first build knowledge abstractions
in pretraining (1), and then transfer these abstractions to a new domain (2),
or adapt them during supervised fine-tuning (3). TX-Ray expresses neurons as
feature preference distributions to quantify fine-grained knowledge transfer or
adaptation and guide human analysis. We find that, similar to Lottery Ticket
based pruning, TX-Ray based pruning can improve test set generalization and
that it can reveal how early stages of self-supervision automatically learn
linguistic abstractions like parts-of-speech.