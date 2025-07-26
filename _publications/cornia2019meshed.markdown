---
layout: publication
title: Meshed-memory Transformer For Image Captioning
authors: Marcella Cornia, Matteo Stefanini, Lorenzo Baraldi, Rita Cucchiara
conference: 2020 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2020
bibkey: cornia2019meshed
citations: 983
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1912.08226'}]
tags: ["CVPR", "Model Architecture"]
short_authors: Cornia et al.
---
Transformer-based architectures represent the state of the art in sequence
modeling tasks like machine translation and language understanding. Their
applicability to multi-modal contexts like image captioning, however, is still
largely under-explored. With the aim of filling this gap, we present M\\(^2\\) - a
Meshed Transformer with Memory for Image Captioning. The architecture improves
both the image encoding and the language generation steps: it learns a
multi-level representation of the relationships between image regions
integrating learned a priori knowledge, and uses a mesh-like connectivity at
decoding stage to exploit low- and high-level features. Experimentally, we
investigate the performance of the M\\(^2\\) Transformer and different
fully-attentive models in comparison with recurrent ones. When tested on COCO,
our proposal achieves a new state of the art in single-model and ensemble
configurations on the "Karpathy" test split and on the online test server. We
also assess its performances when describing objects unseen in the training
set. Trained models and code for reproducing the experiments are publicly
available at: https://github.com/aimagelab/meshed-memory-transformer.