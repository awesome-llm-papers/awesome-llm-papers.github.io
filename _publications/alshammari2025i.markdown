---
layout: publication
title: 'I-con: A Unifying Framework For Representation Learning'
authors: Shaden Alshammari, John Hershey, Axel Feldmann, William T. Freeman, Mark
  Hamilton
conference: No Venue
year: 2025
bibkey: alshammari2025i
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2504.16929'}]
tags: ["Tools"]
short_authors: Alshammari et al.
---
As the field of representation learning grows, there has been a proliferation of different loss functions to solve different classes of problems. We introduce a single information-theoretic equation that generalizes a large collection of modern loss functions in machine learning. In particular, we introduce a framework that shows that several broad classes of machine learning methods are precisely minimizing an integrated KL divergence between two conditional distributions: the supervisory and learned representations. This viewpoint exposes a hidden information geometry underlying clustering, spectral methods, dimensionality reduction, contrastive learning, and supervised learning. This framework enables the development of new loss functions by combining successful techniques from across the literature. We not only present a wide array of proofs, connecting over 23 different approaches, but we also leverage these theoretical results to create state-of-the-art unsupervised image classifiers that achieve a +8% improvement over the prior state-of-the-art on unsupervised classification on ImageNet-1K. We also demonstrate that I-Con can be used to derive principled debiasing methods which improve contrastive representation learners.

https://huggingface.co/discussions/paper/6809ba7d76a4f4f72685478a