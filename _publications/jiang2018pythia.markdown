---
layout: publication
title: 'Pythia V0.1: The Winning Entry To The VQA Challenge 2018'
authors: Yu Jiang, Vivek Natarajan, Xinlei Chen, Marcus Rohrbach, Dhruv Batra, Devi
  Parikh
conference: Arxiv
year: 2018
bibkey: jiang2018pythia
citations: 177
additional_links: [{name: Code, url: 'https://github.com/facebookresearch/pythia'},
  {name: Paper, url: 'https://arxiv.org/abs/1807.09956'}]
tags: ["Datasets", "Evaluation", "Has Code", "Model Architecture"]
short_authors: Jiang et al.
---
This document describes Pythia v0.1, the winning entry from Facebook AI
Research (FAIR)'s A-STAR team to the VQA Challenge 2018.
  Our starting point is a modular re-implementation of the bottom-up top-down
(up-down) model. We demonstrate that by making subtle but important changes to
the model architecture and the learning rate schedule, fine-tuning image
features, and adding data augmentation, we can significantly improve the
performance of the up-down model on VQA v2.0 dataset -- from 65.67% to 70.22%.
  Furthermore, by using a diverse ensemble of models trained with different
features and on different datasets, we are able to significantly improve over
the 'standard' way of ensembling (i.e. same model with different random seeds)
by 1.31%. Overall, we achieve 72.27% on the test-std split of the VQA v2.0
dataset. Our code in its entirety (training, evaluation, data-augmentation,
ensembling) and pre-trained models are publicly available at:
https://github.com/facebookresearch/pythia