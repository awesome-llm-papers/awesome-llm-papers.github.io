---
layout: publication
title: 'Align And Prompt: Video-and-language Pre-training With Entity Prompts'
authors: Dongxu Li, Junnan Li, Hongdong Li, Juan Carlos Niebles, Steven C. H. Hoi
conference: Arxiv
year: 2021
bibkey: li2021align
citations: 683
additional_links: [{name: Code, url: 'https://github.com/salesforce/ALPRO'}, {name: Paper,
    url: 'https://arxiv.org/abs/2112.09583'}]
tags: ["Model Architecture", "Prompting"]
short_authors: Li et al.
---
Video-and-language pre-training has shown promising improvements on various
downstream tasks. Most previous methods capture cross-modal interactions with a
transformer-based multimodal encoder, not fully addressing the misalignment
between unimodal video and text features. Besides, learning fine-grained
visual-language alignment usually requires off-the-shelf object detectors to
provide object information, which is bottlenecked by the detector's limited
vocabulary and expensive computation cost.
  We propose Align and Prompt: an efficient and effective video-and-language
pre-training framework with better cross-modal alignment. First, we introduce a
video-text contrastive (VTC) loss to align unimodal video-text features at the
instance level, which eases the modeling of cross-modal interactions. Then, we
propose a new visually-grounded pre-training task, prompting entity modeling
(PEM), which aims to learn fine-grained region-entity alignment. To achieve
this, we first introduce an entity prompter module, which is trained with VTC
to produce the similarity between a video crop and text prompts instantiated
with entity names. The PEM task then asks the model to predict the entity
pseudo-labels (i.e~normalized similarity scores) for randomly-selected video
crops. The resulting pre-trained model achieves state-of-the-art performance on
both text-video retrieval and videoQA, outperforming prior work by a
substantial margin. Our code and pre-trained models are available at
https://github.com/salesforce/ALPRO.