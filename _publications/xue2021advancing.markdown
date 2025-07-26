---
layout: publication
title: Advancing High-resolution Video-language Representation With Large-scale Video
  Transcriptions
authors: Hongwei Xue, Tiankai Hang, Yanhong Zeng, Yuchong Sun, Bei Liu, Huan Yang,
  Jianlong Fu, Baining Guo
conference: 2022 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2022
bibkey: xue2021advancing
citations: 66
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2111.10337'}]
tags: ["CVPR", "Datasets", "Model Architecture"]
short_authors: Xue et al.
---
We study joint video and language (VL) pre-training to enable cross-modality
learning and benefit plentiful downstream VL tasks. Existing works either
extract low-quality video features or learn limited text embedding, while
neglecting that high-resolution videos and diversified semantics can
significantly improve cross-modality learning. In this paper, we propose a
novel High-resolution and Diversified VIdeo-LAnguage pre-training model
(HD-VILA) for many visual tasks. In particular, we collect a large dataset with
two distinct properties: 1) the first high-resolution dataset including 371.5k
hours of 720p videos, and 2) the most diversified dataset covering 15 popular
YouTube categories. To enable VL pre-training, we jointly optimize the HD-VILA
model by a hybrid Transformer that learns rich spatiotemporal features, and a
multimodal Transformer that enforces interactions of the learned video features
with diversified texts. Our pre-training model achieves new state-of-the-art
results in 10 VL understanding tasks and 2 more novel text-to-visual generation
tasks. For example, we outperform SOTA models with relative increases of 40.4%
R@1 in zero-shot MSR-VTT text-to-video retrieval task and 55.4% in
high-resolution dataset LSMDC. The learned VL embedding is also effective in
generating visually pleasing and semantically relevant results in
text-to-visual editing and super-resolution tasks.