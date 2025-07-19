---
layout: publication
title: 'MMGA: Multimodal Learning With Graph Alignment'
authors: Yang et al.
conference: Proceedings of the 29th ACM International Conference on Multimedia
year: 2022
bibkey: yang2022mmga
citations: 69
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2210.09946'}]
tags: [Training Techniques, Tools, Multimodal Models, Datasets]
---
Multimodal pre-training breaks down the modality barriers and allows the
individual modalities to be mutually augmented with information, resulting in
significant advances in representation learning. However, graph modality, as a
very general and important form of data, cannot be easily interacted with other
modalities because of its non-regular nature. In this paper, we propose MMGA
(Multimodal learning with Graph Alignment), a novel multimodal pre-training
framework to incorporate information from graph (social network), image and
text modalities on social media to enhance user representation learning. In
MMGA, a multi-step graph alignment mechanism is proposed to add the
self-supervision from graph modality to optimize the image and text encoders,
while using the information from the image and text modalities to guide the
graph encoder learning. We conduct experiments on the dataset crawled from
Instagram. The experimental results show that MMGA works well on the dataset
and improves the fans prediction task's performance. We release our dataset,
the first social media multimodal dataset with graph, of 60,000 users labeled
with specific topics based on 2 million posts to facilitate future research.