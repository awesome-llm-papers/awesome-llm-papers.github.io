---
layout: publication
title: Recurrent Topic-transition GAN For Visual Paragraph Generation
authors: Xiaodan Liang, Zhiting Hu, Hao Zhang, Chuang Gan, Eric P. Xing
conference: 2017 IEEE International Conference on Computer Vision (ICCV)
year: 2017
bibkey: liang2017recurrent
citations: 166
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1703.07022'}]
tags: ["ICCV", "Model Architecture", "Training Techniques"]
short_authors: Liang et al.
---
A natural image usually conveys rich semantic content and can be viewed from
different angles. Existing image description methods are largely restricted by
small sets of biased visual paragraph annotations, and fail to cover rich
underlying semantics. In this paper, we investigate a semi-supervised paragraph
generative framework that is able to synthesize diverse and semantically
coherent paragraph descriptions by reasoning over local semantic regions and
exploiting linguistic knowledge. The proposed Recurrent Topic-Transition
Generative Adversarial Network (RTT-GAN) builds an adversarial framework
between a structured paragraph generator and multi-level paragraph
discriminators. The paragraph generator generates sentences recurrently by
incorporating region-based visual and language attention mechanisms at each
step. The quality of generated paragraph sentences is assessed by multi-level
adversarial discriminators from two aspects, namely, plausibility at sentence
level and topic-transition coherence at paragraph level. The joint adversarial
training of RTT-GAN drives the model to generate realistic paragraphs with
smooth logical transition between sentence topics. Extensive quantitative
experiments on image and video paragraph datasets demonstrate the effectiveness
of our RTT-GAN in both supervised and semi-supervised settings. Qualitative
results on telling diverse stories for an image also verify the
interpretability of RTT-GAN.