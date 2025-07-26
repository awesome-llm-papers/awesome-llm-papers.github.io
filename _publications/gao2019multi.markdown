---
layout: publication
title: Multi-modality Latent Interaction Network For Visual Question Answering
authors: Peng Gao, Haoxuan You, Zhanpeng Zhang, Xiaogang Wang, Hongsheng Li
conference: 2019 IEEE/CVF International Conference on Computer Vision (ICCV)
year: 2019
bibkey: gao2019multi
citations: 69
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1908.04289'}]
tags: ["ICCV", "Model Architecture"]
short_authors: Gao et al.
---
Exploiting relationships between visual regions and question words have
achieved great success in learning multi-modality features for Visual Question
Answering (VQA). However, we argue that existing methods mostly model relations
between individual visual regions and words, which are not enough to correctly
answer the question. From humans' perspective, answering a visual question
requires understanding the summarizations of visual and language information.
In this paper, we proposed the Multi-modality Latent Interaction module (MLI)
to tackle this problem. The proposed module learns the cross-modality
relationships between latent visual and language summarizations, which
summarize visual regions and question into a small number of latent
representations to avoid modeling uninformative individual region-word
relations. The cross-modality information between the latent summarizations are
propagated to fuse valuable information from both modalities and are used to
update the visual and word features. Such MLI modules can be stacked for
several stages to model complex and latent relations between the two modalities
and achieves highly competitive performance on public VQA benchmarks, VQA v2.0
and TDIUC . In addition, we show that the performance of our methods could be
significantly improved by combining with pre-trained language model BERT.