---
layout: publication
title: REMIND Your Neural Network To Prevent Catastrophic Forgetting
authors: Tyler L. Hayes, Kushal Kafle, Robik Shrestha, Manoj Acharya, Christopher
  Kanan
conference: Lecture Notes in Computer Science
year: 2020
bibkey: hayes2019remind
citations: 198
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1910.02509'}]
tags: ["Fine-Tuning", "Training Techniques"]
short_authors: Hayes et al.
---
People learn throughout life. However, incrementally updating conventional
neural networks leads to catastrophic forgetting. A common remedy is replay,
which is inspired by how the brain consolidates memory. Replay involves
fine-tuning a network on a mixture of new and old instances. While there is
neuroscientific evidence that the brain replays compressed memories, existing
methods for convolutional networks replay raw images. Here, we propose REMIND,
a brain-inspired approach that enables efficient replay with compressed
representations. REMIND is trained in an online manner, meaning it learns one
example at a time, which is closer to how humans learn. Under the same
constraints, REMIND outperforms other methods for incremental class learning on
the ImageNet ILSVRC-2012 dataset. We probe REMIND's robustness to data ordering
schemes known to induce catastrophic forgetting. We demonstrate REMIND's
generality by pioneering online learning for Visual Question Answering (VQA).