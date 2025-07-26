---
layout: publication
title: Escaping The Big Data Paradigm With Compact Transformers
authors: Ali Hassani, Steven Walton, Nikhil Shah, Abulikemu Abuduweili, Jiachen Li,
  Humphrey Shi
conference: Arxiv
year: 2021
bibkey: hassani2021escaping
citations: 270
additional_links: [{name: Code, url: 'https://github.com/SHI-Labs/Compact-Transformers'},
  {name: Paper, url: 'https://arxiv.org/abs/2104.05704'}]
tags: ["Efficiency", "Model Architecture"]
short_authors: Hassani et al.
---
With the rise of Transformers as the standard for language processing, and
their advancements in computer vision, there has been a corresponding growth in
parameter size and amounts of training data. Many have come to believe that
because of this, transformers are not suitable for small sets of data. This
trend leads to concerns such as: limited availability of data in certain
scientific domains and the exclusion of those with limited resource from
research in the field. In this paper, we aim to present an approach for
small-scale learning by introducing Compact Transformers. We show for the first
time that with the right size, convolutional tokenization, transformers can
avoid overfitting and outperform state-of-the-art CNNs on small datasets. Our
models are flexible in terms of model size, and can have as little as 0.28M
parameters while achieving competitive results. Our best model can reach 98%
accuracy when training from scratch on CIFAR-10 with only 3.7M parameters,
which is a significant improvement in data-efficiency over previous Transformer
based models being over 10x smaller than other transformers and is 15% the size
of ResNet50 while achieving similar performance. CCT also outperforms many
modern CNN based approaches, and even some recent NAS-based approaches.
Additionally, we obtain a new SOTA result on Flowers-102 with 99.76% top-1
accuracy, and improve upon the existing baseline on ImageNet (82.71% accuracy
with 29% as many parameters as ViT), as well as NLP tasks. Our simple and
compact design for transformers makes them more feasible to study for those
with limited computing resources and/or dealing with small datasets, while
extending existing research efforts in data efficient transformers. Our code
and pre-trained models are publicly available at
https://github.com/SHI-Labs/Compact-Transformers.