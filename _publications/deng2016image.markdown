---
layout: publication
title: Image-to-markup Generation With Coarse-to-fine Attention
authors: Yuntian Deng, Anssi Kanervisto, Jeffrey Ling, Alexander M. Rush
conference: Arxiv
year: 2016
bibkey: deng2016image
citations: 87
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1609.04938'}]
tags: ["Model Architecture"]
short_authors: Deng et al.
---
We present a neural encoder-decoder model to convert images into
presentational markup based on a scalable coarse-to-fine attention mechanism.
Our method is evaluated in the context of image-to-LaTeX generation, and we
introduce a new dataset of real-world rendered mathematical expressions paired
with LaTeX markup. We show that unlike neural OCR techniques using CTC-based
models, attention-based approaches can tackle this non-standard OCR task. Our
approach outperforms classical mathematical OCR systems by a large margin on
in-domain rendered data, and, with pretraining, also performs well on
out-of-domain handwritten data. To reduce the inference complexity associated
with the attention-based approaches, we introduce a new coarse-to-fine
attention layer that selects a support region before applying attention.