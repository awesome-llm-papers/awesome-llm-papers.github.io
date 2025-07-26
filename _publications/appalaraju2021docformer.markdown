---
layout: publication
title: 'Docformer: End-to-end Transformer For Document Understanding'
authors: Srikar Appalaraju, Bhavan Jasani, Bhargava Urala Kota, Yusheng Xie, R. Manmatha
conference: 2021 IEEE/CVF International Conference on Computer Vision (ICCV)
year: 2021
bibkey: appalaraju2021docformer
citations: 191
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2106.11539'}]
tags: ["ICCV", "Model Architecture"]
short_authors: Appalaraju et al.
---
We present DocFormer -- a multi-modal transformer based architecture for the
task of Visual Document Understanding (VDU). VDU is a challenging problem which
aims to understand documents in their varied formats (forms, receipts etc.) and
layouts. In addition, DocFormer is pre-trained in an unsupervised fashion using
carefully designed tasks which encourage multi-modal interaction. DocFormer
uses text, vision and spatial features and combines them using a novel
multi-modal self-attention layer. DocFormer also shares learned spatial
embeddings across modalities which makes it easy for the model to correlate
text to visual tokens and vice versa. DocFormer is evaluated on 4 different
datasets each with strong baselines. DocFormer achieves state-of-the-art
results on all of them, sometimes beating models 4x its size (in no. of
parameters).