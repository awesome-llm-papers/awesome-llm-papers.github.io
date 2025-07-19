---
layout: publication
title: Investigating Audio, Visual, And Text Fusion Methods For End-to-end Automatic
  Personality Prediction
authors: Kampman et al.
conference: 'Proceedings of the 56th Annual Meeting of the Association for Computational
  Linguistics (Volume 2: Short Papers)'
year: 2018
bibkey: kampman2018investigating
citations: 51
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1805.00705'}]
tags: [Model Architecture, Merging, ACL, Agentic, RAG, Multimodal Models]
---
We propose a tri-modal architecture to predict Big Five personality trait
scores from video clips with different channels for audio, text, and video
data. For each channel, stacked Convolutional Neural Networks are employed. The
channels are fused both on decision-level and by concatenating their respective
fully connected layers. It is shown that a multimodal fusion approach
outperforms each single modality channel, with an improvement of 9.4% over the
best individual modality (video). Full backpropagation is also shown to be
better than a linear combination of modalities, meaning complex interactions
between modalities can be leveraged to build better models. Furthermore, we can
see the prediction relevance of each modality for each trait. The described
model can be used to increase the emotional intelligence of virtual agents.