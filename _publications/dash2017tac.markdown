---
layout: publication
title: TAC-GAN - Text Conditioned Auxiliary Classifier Generative Adversarial Network
authors: Dash et al.
conference: Arxiv
year: 2017
bibkey: dash2017tac
citations: 108
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1703.06412'}]
tags: [RAG, Security, Training Techniques, Datasets]
---
In this work, we present the Text Conditioned Auxiliary Classifier Generative
Adversarial Network, (TAC-GAN) a text to image Generative Adversarial Network
(GAN) for synthesizing images from their text descriptions. Former approaches
have tried to condition the generative process on the textual data; but allying
it to the usage of class information, known to diversify the generated samples
and improve their structural coherence, has not been explored. We trained the
presented TAC-GAN model on the Oxford-102 dataset of flowers, and evaluated the
discriminability of the generated images with Inception-Score, as well as their
diversity using the Multi-Scale Structural Similarity Index (MS-SSIM). Our
approach outperforms the state-of-the-art models, i.e., its inception score is
3.45, corresponding to a relative increase of 7.8% compared to the recently
introduced StackGan. A comparison of the mean MS-SSIM scores of the training
and generated samples per class shows that our approach is able to generate
highly diverse images with an average MS-SSIM of 0.14 over all generated
classes.