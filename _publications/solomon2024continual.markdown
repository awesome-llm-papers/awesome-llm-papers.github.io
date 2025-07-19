---
layout: publication
title: Continual Learning With Task Specialist
authors: Solomon et al.
conference: 2019 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2024
bibkey: solomon2024continual
citations: 185
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2409.17806'}]
tags: [Training Techniques, CVPR, Reinforcement Learning, Datasets, Merging]
---
Continual learning (CL) adapt the deep learning scenarios with timely updated
datasets. However, existing CL models suffer from the catastrophic forgetting
issue, where new knowledge replaces past learning. In this paper, we propose
Continual Learning with Task Specialists (CLTS) to address the issues of
catastrophic forgetting and limited labelled data in real-world datasets by
performing class incremental learning of the incoming stream of data. The model
consists of Task Specialists (T S) and Task Predictor (T P ) with pre-trained
Stable Diffusion (SD) module. Here, we introduce a new specialist to handle a
new task sequence and each T S has three blocks; i) a variational autoencoder
(V AE) to learn the task distribution in a low dimensional latent space, ii) a
K-Means block to perform data clustering and iii) Bootstrapping Language-Image
Pre-training (BLIP ) model to generate a small batch of captions from the input
data. These captions are fed as input to the pre-trained stable diffusion model
(SD) for the generation of task samples. The proposed model does not store any
task samples for replay, instead uses generated samples from SD to train the T
P module. A comparison study with four SOTA models conducted on three
real-world datasets shows that the proposed model outperforms all the selected
baselines