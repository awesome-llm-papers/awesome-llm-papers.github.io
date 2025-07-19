---
layout: publication
title: 'The Devil Is In The Detail: Simple Tricks Improve Systematic Generalization
  Of Transformers'
authors: "Csord\xE1s R\xF3bert, Irie Kazuki, Schmidhuber J\xFCrgen"
conference: Proceedings of the 2021 Conference on Empirical Methods in Natural Language
  Processing
year: 2021
bibkey: "csord\xE1s2021devil"
citations: 51
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2108.12284'}]
tags: [EMNLP, Transformer, Model Architecture, Reinforcement Learning, Datasets]
---
Recently, many datasets have been proposed to test the systematic
generalization ability of neural networks. The companion baseline Transformers,
typically trained with default hyper-parameters from standard tasks, are shown
to fail dramatically. Here we demonstrate that by revisiting model
configurations as basic as scaling of embeddings, early stopping, relative
positional embedding, and Universal Transformer variants, we can drastically
improve the performance of Transformers on systematic generalization. We report
improvements on five popular datasets: SCAN, CFQ, PCFG, COGS, and Mathematics
dataset. Our models improve accuracy from 50% to 85% on the PCFG productivity
split, and from 35% to 81% on COGS. On SCAN, relative positional embedding
largely mitigates the EOS decision problem (Newman et al., 2020), yielding 100%
accuracy on the length split with a cutoff at 26. Importantly, performance
differences between these models are typically invisible on the IID data split.
This calls for proper generalization validation sets for developing neural
networks that generalize systematically. We publicly release the code to
reproduce our results.