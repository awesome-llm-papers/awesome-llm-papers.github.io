---
layout: publication
title: 'End-to-end Speech-translation With Knowledge Distillation: FBK@IWSLT2020'
authors: Marco Gaido, Mattia Antonino di Gangi, Matteo Negri, Marco Turchi
conference: Proceedings of the 17th International Conference on Spoken Language Translation
year: 2020
bibkey: gaido2020end
citations: 64
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2006.02965'}]
tags: ["Efficiency", "Fine-Tuning", "Model Architecture", "Training Techniques"]
short_authors: Gaido et al.
---
This paper describes FBK's participation in the IWSLT 2020 offline speech
translation (ST) task. The task evaluates systems' ability to translate English
TED talks audio into German texts. The test talks are provided in two versions:
one contains the data already segmented with automatic tools and the other is
the raw data without any segmentation. Participants can decide whether to work
on custom segmentation or not. We used the provided segmentation. Our system is
an end-to-end model based on an adaptation of the Transformer for speech data.
Its training process is the main focus of this paper and it is based on: i)
transfer learning (ASR pretraining and knowledge distillation), ii) data
augmentation (SpecAugment, time stretch and synthetic data), iii) combining
synthetic and real data marked as different domains, and iv) multi-task
learning using the CTC loss. Finally, after the training with word-level
knowledge distillation is complete, our ST models are fine-tuned using label
smoothed cross entropy. Our best model scored 29 BLEU on the MuST-C En-De test
set, which is an excellent result compared to recent papers, and 23.7 BLEU on
the same data segmented with VAD, showing the need for researching solutions
addressing this specific data condition.