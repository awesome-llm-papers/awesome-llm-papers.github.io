---
layout: publication
title: 'Show, Adapt And Tell: Adversarial Training Of Cross-domain Image Captioner'
authors: Chen et al.
conference: 2017 IEEE International Conference on Computer Vision (ICCV)
year: 2017
bibkey: chen2017show
citations: 93
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1705.00930'}]
tags: [RAG, ICCV, Training Techniques, Reinforcement Learning, Security, Datasets]
---
Impressive image captioning results are achieved in domains with plenty of
training image and sentence pairs (e.g., MSCOCO). However, transferring to a
target domain with significant domain shifts but no paired training data
(referred to as cross-domain image captioning) remains largely unexplored. We
propose a novel adversarial training procedure to leverage unpaired data in the
target domain. Two critic networks are introduced to guide the captioner,
namely domain critic and multi-modal critic. The domain critic assesses whether
the generated sentences are indistinguishable from sentences in the target
domain. The multi-modal critic assesses whether an image and its generated
sentence are a valid pair. During training, the critics and captioner act as
adversaries -- captioner aims to generate indistinguishable sentences, whereas
critics aim at distinguishing them. The assessment improves the captioner
through policy gradient updates. During inference, we further propose a novel
critic-based planning method to select high-quality sentences without
additional supervision (e.g., tags). To evaluate, we use MSCOCO as the source
domain and four other datasets (CUB-200-2011, Oxford-102, TGIF, and Flickr30k)
as the target domains. Our method consistently performs well on all datasets.
In particular, on CUB-200-2011, we achieve 21.8% CIDEr-D improvement after
adaptation. Utilizing critics during inference further gives another 4.5%
boost.