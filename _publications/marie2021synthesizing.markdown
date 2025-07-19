---
layout: publication
title: Synthesizing Monolingual Data For Neural Machine Translation
authors: Marie Benjamin, Fujita Atsushi
conference: 'Proceedings of the 54th Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)'
year: 2021
bibkey: marie2021synthesizing
citations: 598
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2101.12462'}]
tags: [Model Architecture, Training Techniques, ACL, RAG, GPT]
---
In neural machine translation (NMT), monolingual data in the target language
are usually exploited through a method so-called "back-translation" to
synthesize additional training parallel data. The synthetic data have been
shown helpful to train better NMT, especially for low-resource language pairs
and domains. Nonetheless, large monolingual data in the target domains or
languages are not always available to generate large synthetic parallel data.
In this work, we propose a new method to generate large synthetic parallel data
leveraging very small monolingual data in a specific domain. We fine-tune a
pre-trained GPT-2 model on such small in-domain monolingual data and use the
resulting model to generate a large amount of synthetic in-domain monolingual
data. Then, we perform back-translation, or forward translation, to generate
synthetic in-domain parallel data. Our preliminary experiments on three
language pairs and five domains show the effectiveness of our method to
generate fully synthetic but useful in-domain parallel data for improving NMT
in all configurations. We also show promising results in extreme adaptation for
personalized NMT.