---
layout: publication
title: Paraphrase Augmented Task-oriented Dialog Generation
authors: Silin Gao, Yichi Zhang, Zhijian Ou, Zhou Yu
conference: Proceedings of the 58th Annual Meeting of the Association for Computational
  Linguistics
year: 2020
bibkey: gao2020paraphrase
citations: 77
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2004.07462'}]
tags: ["Datasets", "Training Techniques"]
short_authors: Gao et al.
---
Neural generative models have achieved promising performance on dialog
generation tasks if given a huge data set. However, the lack of high-quality
dialog data and the expensive data annotation process greatly limit their
application in real-world settings. We propose a paraphrase augmented response
generation (PARG) framework that jointly trains a paraphrase model and a
response generation model to improve the dialog generation performance. We also
design a method to automatically construct paraphrase training data set based
on dialog state and dialog act labels. PARG is applicable to various dialog
generation models, such as TSCP (Lei et al., 2018) and DAMD (Zhang et al.,
2019). Experimental results show that the proposed framework improves these
state-of-the-art dialog models further on CamRest676 and MultiWOZ. PARG also
significantly outperforms other data augmentation methods in dialog generation
tasks, especially under low resource settings.