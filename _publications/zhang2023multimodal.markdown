---
layout: publication
title: Multimodal Pre-training Framework For Sequential Recommendation Via Contrastive
  Learning
authors: Lingzi Zhang, Xin Zhou, Zhiwei Zeng, Zhiqi Shen
conference: Arxiv
year: 2023
bibkey: zhang2023multimodal
citations: 68
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2303.11879'}]
tags: ["Datasets", "Training Techniques"]
short_authors: Zhang et al.
---
Current multimodal sequential recommendation models are often unable to
effectively explore and capture correlations among behavior sequences of users
and items across different modalities, either neglecting correlations among
sequence representations or inadequately capturing associations between
multimodal data and sequence data in their representations. To address this
problem, we explore multimodal pre-training in the context of sequential
recommendation, with the aim of enhancing fusion and utilization of multimodal
information. We propose a novel Multimodal Pre-training for Sequential
Recommendation (MP4SR) framework, which utilizes contrastive losses to capture
the correlation among different modality sequences of users, as well as the
correlation among different modality sequences of users and items. MP4SR
consists of three key components: 1) multimodal feature extraction, 2) a
backbone network, Multimodal Mixup Sequence Encoder (M2SE), and 3) pre-training
tasks. After utilizing pre-trained encoders to generate initial multimodal
features of items, M2SE adopts a complementary sequence mixup strategy to fuse
different modality sequences, and leverages contrastive learning to capture
modality interactions at the sequence-to-sequence and sequence-to-item levels.
Extensive experiments on four real-world datasets demonstrate that MP4SR
outperforms state-of-the-art approaches in both normal and cold-start settings.
We further highlight the efficacy of incorporating multimodal pre-training in
sequential recommendation representation learning, serving as an effective
regularizer and optimizing the parameter space for the recommendation task.