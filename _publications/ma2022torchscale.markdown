---
layout: publication
title: 'Torchscale: Transformers At Scale'
authors: Ma et al.
conference: 2021 IEEE/CVF International Conference on Computer Vision (ICCV)
year: 2022
bibkey: ma2022torchscale
citations: 247
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2211.13184'}]
tags: [ICCV, Training Techniques, Tools, Transformer, Model Architecture, Efficiency
    And Optimization, Language Modeling, Large Scale Training]
---
Large Transformers have achieved state-of-the-art performance across many
tasks. Most open-source libraries on scaling Transformers focus on improving
training or inference with better parallelization. In this work, we present
TorchScale, an open-source toolkit that allows researchers and developers to
scale up Transformers efficiently and effectively. TorchScale has the
implementation of several modeling techniques, which can improve modeling
generality and capability, as well as training stability and efficiency.
Experimental results on language modeling and neural machine translation
demonstrate that TorchScale can successfully scale Transformers to different
sizes without tears. The library is available at https://aka.ms/torchscale.