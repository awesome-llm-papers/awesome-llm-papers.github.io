---
layout: publication
title: Pre-training Graph Transformer With Multimodal Side Information For Recommendation
authors: Yong Liu, Susen Yang, Chenyi Lei, Guoxin Wang, Haihong Tang, Juyong Zhang,
  Aixin Sun, Chunyan Miao
conference: Proceedings of the 29th ACM International Conference on Multimedia
year: 2021
bibkey: liu2020pre
citations: 62
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2010.12284'}]
tags: ["Model Architecture", "Training Techniques"]
short_authors: Liu et al.
---
Side information of items, e.g., images and text description, has shown to be
effective in contributing to accurate recommendations. Inspired by the recent
success of pre-training models on natural language and images, we propose a
pre-training strategy to learn item representations by considering both item
side information and their relationships. We relate items by common user
activities, e.g., co-purchase, and construct a homogeneous item graph. This
graph provides a unified view of item relations and their associated side
information in multimodality. We develop a novel sampling algorithm named
MCNSampling to select contextual neighbors for each item. The proposed
Pre-trained Multimodal Graph Transformer (PMGT) learns item representations
with two objectives: 1) graph structure reconstruction, and 2) masked node
feature reconstruction. Experimental results on real datasets demonstrate that
the proposed PMGT model effectively exploits the multimodality side information
to achieve better accuracies in downstream tasks including item recommendation,
item classification, and click-through ratio prediction. We also report a case
study of testing the proposed PMGT model in an online setting with 600 thousand
users.