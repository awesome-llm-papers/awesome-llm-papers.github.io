---
layout: publication
title: 'Regmix: Data Mixture As Regression For Language Model Pre-training'
authors: Qian Liu, Xiaosen Zheng, Niklas Muennighoff, Guangtao Zeng, Longxu Dou, Tianyu
  Pang, Jing Jiang, Min Lin
conference: No Venue
year: 2024
bibkey: liu2024regmix
additional_links: [{name: Code, url: 'https://github.com/sail-sg/regmix'}, {name: Code,
    url: 'https://huggingface.co/discussions/paper/668375672ca1c52c2744c871'}, {name: Paper,
    url: 'https://arxiv.org/abs/hf2407.01492'}]
tags: ["Has Code", "Training Techniques"]
short_authors: Liu et al.
---
The data mixture for large language model pre-training significantly impacts performance, yet how to determine an effective mixture remains unclear. We propose RegMix to automatically identify a high-performing data mixture by formulating it as a regression task. RegMix involves training a set of small models with diverse data mixtures and fitting a regression model to predict their performance given their respective mixtures. With the fitted regression model, we simulate the top-ranked mixture and use it to train a large-scale model with orders of magnitude more compute. To empirically validate RegMix, we train 512 models with 1M parameters for 1B tokens of different mixtures to fit the regression model and find the optimal mixture. Using this mixture we train a 1B parameter model for 25B tokens (i.e. 1000x larger and 25x longer) which we find performs best among 64 candidate 1B parameter models with other mixtures. Further, our method demonstrates superior performance compared to human selection and achieves results that match or surpass DoReMi, while utilizing only 10% of the compute budget. Our experiments also show that (1) Data mixtures significantly impact performance with single-task performance variations of up to 14.6%; (2) Web corpora rather than data perceived as high-quality like Wikipedia have the strongest positive correlation with downstream performance; (3) Domains interact in complex ways often contradicting common sense, thus automatic approaches like RegMix are needed; (4) Data mixture effects transcend scaling laws, and our approach captures the complexity by considering all domains together. Our code is available at https://github.com/sail-sg/regmix.

https://huggingface.co/discussions/paper/668375672ca1c52c2744c871