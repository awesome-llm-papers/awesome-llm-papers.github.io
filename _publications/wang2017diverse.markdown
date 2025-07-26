---
layout: publication
title: Diverse And Accurate Image Description Using A Variational Auto-encoder With
  An Additive Gaussian Encoding Space
authors: Liwei Wang, Alexander G. Schwing, Svetlana Lazebnik
conference: Arxiv
year: 2017
bibkey: wang2017diverse
citations: 128
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1711.07068'}]
tags: ["Model Architecture"]
short_authors: Liwei Wang, Alexander G. Schwing, Svetlana Lazebnik
---
This paper explores image caption generation using conditional variational
auto-encoders (CVAEs). Standard CVAEs with a fixed Gaussian prior yield
descriptions with too little variability. Instead, we propose two models that
explicitly structure the latent space around \\(K\\) components corresponding to
different types of image content, and combine components to create priors for
images that contain multiple types of content simultaneously (e.g., several
kinds of objects). Our first model uses a Gaussian Mixture model (GMM) prior,
while the second one defines a novel Additive Gaussian (AG) prior that linearly
combines component means. We show that both models produce captions that are
more diverse and more accurate than a strong LSTM baseline or a "vanilla" CVAE
with a fixed Gaussian prior, with AG-CVAE showing particular promise.