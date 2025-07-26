---
layout: publication
title: Variational Recurrent Neural Machine Translation
authors: Jinsong Su, Shan Wu, Deyi Xiong, Yaojie Lu, Xianpei Han, Biao Zhang
conference: Proceedings of the AAAI Conference on Artificial Intelligence
year: 2018
bibkey: su2018variational
citations: 78
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1801.05119'}]
tags: ["AAAI", "Applications", "Training Techniques"]
short_authors: Su et al.
---
Partially inspired by successful applications of variational recurrent neural
networks, we propose a novel variational recurrent neural machine translation
(VRNMT) model in this paper. Different from the variational NMT, VRNMT
introduces a series of latent random variables to model the translation
procedure of a sentence in a generative way, instead of a single latent
variable. Specifically, the latent random variables are included into the
hidden states of the NMT decoder with elements from the variational
autoencoder. In this way, these variables are recurrently generated, which
enables them to further capture strong and complex dependencies among the
output translations at different timesteps. In order to deal with the
challenges in performing efficient posterior inference and large-scale training
during the incorporation of latent variables, we build a neural posterior
approximator, and equip it with a reparameterization technique to estimate the
variational lower bound. Experiments on Chinese-English and English-German
translation tasks demonstrate that the proposed model achieves significant
improvements over both the conventional and variational NMT models.