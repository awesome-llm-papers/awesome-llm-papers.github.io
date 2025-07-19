---
layout: publication
title: 'Noisyicl: A Little Noise In Model Parameters Calibrates In-context Learning'
authors: Zhao Yufeng, Sakai Yoshihiro, Inoue Naoya
conference: Nature Neuroscience
year: 2024
bibkey: zhao2024noisyicl
citations: 626
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2402.05515'}]
tags: [Datasets, Ethics And Bias, In Context Learning]
---
In-Context Learning (ICL) is suffering from unsatisfactory performance and
under-calibration due to high prior bias and unfaithful confidence. Some
previous works fine-tuned language models for better ICL performance with
enormous datasets and computing costs. In this paper, we propose NoisyICL,
simply perturbing the model parameters by random noises to strive for better
performance and calibration. Our experiments on two models and 12 downstream
datasets show that NoisyICL can help ICL produce more accurate predictions. Our
further analysis indicates that NoisyICL enables the model to provide more fair
predictions, and also with more faithful confidence. Therefore, we believe that
NoisyICL is an effective calibration of ICL. Our experimental code is uploaded
to Github.