---
layout: publication
title: 'Camel: Mean Teacher Learning For Image Captioning'
authors: Manuele Barraco et al.
conference: Arxiv
year: 2022
citations: 23
bibkey: barraco2022mean
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2202.10492'}, {name: Code,
    url: 'https://github.com/aimagelab/camel'}]
tags: [Distillation, Transformer, Training Techniques, RAG, Efficiency and Optimization,
  Has Code, Model Architecture]
---
Describing images in natural language is a fundamental step towards the
automatic modeling of connections between the visual and textual modalities. In
this paper we present CaMEL, a novel Transformer-based architecture for image
captioning. Our proposed approach leverages the interaction of two
interconnected language models that learn from each other during the training
phase. The interplay between the two language models follows a mean teacher
learning paradigm with knowledge distillation. Experimentally, we assess the
effectiveness of the proposed solution on the COCO dataset and in conjunction
with different visual feature extractors. When comparing with existing
proposals, we demonstrate that our model provides state-of-the-art caption
quality with a significantly reduced number of parameters. According to the
CIDEr metric, we obtain a new state of the art on COCO when training without
using external data. The source code and trained models are publicly available
at: https://github.com/aimagelab/camel.