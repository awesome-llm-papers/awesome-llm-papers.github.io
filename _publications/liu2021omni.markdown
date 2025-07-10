---
layout: publication
title: 'OPT: Omni-perception Pre-trainer For Cross-modal Understanding And Generation'
authors: Jing Liu et al.
conference: Arxiv
year: 2021
citations: 18
bibkey: liu2021omni
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2107.00249'}]
tags: [Tools, Training Techniques, Multimodal Models, Pre-Training]
---
In this paper, we propose an Omni-perception Pre-Trainer (OPT) for
cross-modal understanding and generation, by jointly modeling visual, text and
audio resources. OPT is constructed in an encoder-decoder framework, including
three single-modal encoders to generate token-based embeddings for each
modality, a cross-modal encoder to encode the correlations among the three
modalities, and two cross-modal decoders to generate text and image
respectively. For the OPT's pre-training, we design a multi-task pretext
learning scheme to model multi-modal resources from three different data
granularities, \ie, token-, modality-, and sample-level modeling, through which
OPT learns to align and translate among different modalities. The pre-training
task is carried out on a large amount of image-text-audio triplets from Open
Images. Experimental results show that OPT can learn strong image-text-audio
multi-modal representations and achieve promising results on a variety of
cross-modal understanding and generation tasks.