---
layout: publication
title: An Empirical Study Of Autoregressive Pre-training From Videos
authors: Jathushan Rajasegaran, Ilija Radosavovic, Rahul Ravishankar, Yossi Gandelsman,
  Christoph Feichtenhofer, Jitendra Malik
conference: No Venue
year: 2025
bibkey: rajasegaran2025empirical
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2501.05453'}]
tags: ["Model Architecture", "Training Techniques"]
short_authors: Rajasegaran et al.
---
We empirically study autoregressive pre-training from videos. To perform our study, we construct a series of autoregressive video models, called Toto. We treat videos as sequences of visual tokens and train transformer models to autoregressively predict future tokens. Our models are pre-trained on a diverse dataset of videos and images comprising over 1 trillion visual tokens. We explore different architectural, training, and inference design choices. We evaluate the learned visual representations on a range of downstream tasks including image recognition, video classification, object tracking, and robotics. Our results demonstrate that, despite minimal inductive biases, autoregressive pre-training leads to competitive performance across all benchmarks. Finally, we find that scaling our video models results in similar scaling curves to those seen in language models, albeit with a different rate. More details at https://brjathu.github.io/toto/

https://huggingface.co/discussions/paper/67809ced063dd44ffb1de947