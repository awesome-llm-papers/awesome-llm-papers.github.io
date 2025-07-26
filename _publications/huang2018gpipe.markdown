---
layout: publication
title: 'Gpipe: Efficient Training Of Giant Neural Networks Using Pipeline Parallelism'
authors: Yanping Huang, Youlong Cheng, Ankur Bapna, Orhan Firat, Mia Xu Chen, Dehao
  Chen, Hyoukjoong Lee, Jiquan Ngiam, Quoc V. Le, Yonghui Wu, Zhifeng Chen
conference: Arxiv
year: 2018
bibkey: huang2018gpipe
citations: 830
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1811.06965'}]
tags: ["Model Architecture", "Training Techniques"]
short_authors: Huang et al.
---
Scaling up deep neural network capacity has been known as an effective
approach to improving model quality for several different machine learning
tasks. In many cases, increasing model capacity beyond the memory limit of a
single accelerator has required developing special algorithms or
infrastructure. These solutions are often architecture-specific and do not
transfer to other tasks. To address the need for efficient and task-independent
model parallelism, we introduce GPipe, a pipeline parallelism library that
allows scaling any network that can be expressed as a sequence of layers. By
pipelining different sub-sequences of layers on separate accelerators, GPipe
provides the flexibility of scaling a variety of different networks to gigantic
sizes efficiently. Moreover, GPipe utilizes a novel batch-splitting pipelining
algorithm, resulting in almost linear speedup when a model is partitioned
across multiple accelerators. We demonstrate the advantages of GPipe by
training large-scale neural networks on two different tasks with distinct
network architectures: (i) Image Classification: We train a
557-million-parameter AmoebaNet model and attain a top-1 accuracy of 84.4% on
ImageNet-2012, (ii) Multilingual Neural Machine Translation: We train a single
6-billion-parameter, 128-layer Transformer model on a corpus spanning over 100
languages and achieve better quality than all bilingual models.