---
layout: publication
title: 'Cascadexml: Rethinking Transformers For End-to-end Multi-resolution Training
  In Extreme Multi-label Classification'
authors: Kharbanda et al.
conference: Proceedings of the 26th ACM SIGKDD International Conference on Knowledge
  Discovery &amp; Data Mining
year: 2022
bibkey: kharbanda2022cascadexml
citations: 127
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2211.00640'}]
tags: [RAG, Training Techniques, Attention Mechanism, Alt, Evaluation, Transformer,
  Model Architecture, Datasets, KDD]
---
Extreme Multi-label Text Classification (XMC) involves learning a classifier
that can assign an input with a subset of most relevant labels from millions of
label choices. Recent approaches, such as XR-Transformer and LightXML, leverage
a transformer instance to achieve state-of-the-art performance. However, in
this process, these approaches need to make various trade-offs between
performance and computational requirements. A major shortcoming, as compared to
the Bi-LSTM based AttentionXML, is that they fail to keep separate feature
representations for each resolution in a label tree. We thus propose
CascadeXML, an end-to-end multi-resolution learning pipeline, which can harness
the multi-layered architecture of a transformer model for attending to
different label resolutions with separate feature representations. CascadeXML
significantly outperforms all existing approaches with non-trivial gains
obtained on benchmark datasets consisting of up to three million labels. Code
for CascadeXML will be made publicly available at
https://github.com/xmc-aalto/cascadexml.