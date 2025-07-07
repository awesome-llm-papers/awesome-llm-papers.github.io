---
layout: publication
title: 'Wenlan: Bridging Vision And Language By Large-scale Multi-modal Pre-training'
authors: Yuqi Huo et al.
conference: Arxiv
year: 2021
citations: 77
bibkey: huo2021bridging
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2103.06561'}]
tags: [Training Techniques, Pre-Training, Tools, Reinforcement Learning, Multimodal
    Models]
---
Multi-modal pre-training models have been intensively explored to bridge
vision and language in recent years. However, most of them explicitly model the
cross-modal interaction between image-text pairs, by assuming that there exists
strong semantic correlation between the text and image modalities. Since this
strong assumption is often invalid in real-world scenarios, we choose to
implicitly model the cross-modal correlation for large-scale multi-modal
pre-training, which is the focus of the Chinese project `WenLan' led by our
team. Specifically, with the weak correlation assumption over image-text pairs,
we propose a two-tower pre-training model called BriVL within the cross-modal
contrastive learning framework. Unlike OpenAI CLIP that adopts a simple
contrastive learning method, we devise a more advanced algorithm by adapting
the latest method MoCo into the cross-modal scenario. By building a large
queue-based dictionary, our BriVL can incorporate more negative samples in
limited GPU resources. We further construct a large Chinese multi-source
image-text dataset called RUC-CAS-WenLan for pre-training our BriVL model.
Extensive experiments demonstrate that the pre-trained BriVL model outperforms
both UNITER and OpenAI CLIP on various downstream tasks.