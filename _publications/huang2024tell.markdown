---
layout: publication
title: 'Tell Me What To Track: Infusing Robust Language Guidance For Enhanced Referring
  Multi-object Tracking'
authors: Huang et al.
conference: 2023 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2024
bibkey: huang2024tell
citations: 53
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2412.12561'}]
tags: [Multimodal Models, Reinforcement Learning, CVPR, Merging]
---
Referring multi-object tracking (RMOT) is an emerging cross-modal task that
aims to localize an arbitrary number of targets based on a language expression
and continuously track them in a video. This intricate task involves reasoning
on multi-modal data and precise target localization with temporal association.
However, prior studies overlook the imbalanced data distribution between
newborn targets and existing targets due to the nature of the task. In
addition, they only indirectly fuse multi-modal features, struggling to deliver
clear guidance on newborn target detection. To solve the above issues, we
conduct a collaborative matching strategy to alleviate the impact of the
imbalance, boosting the ability to detect newborn targets while maintaining
tracking performance. In the encoder, we integrate and enhance the cross-modal
and multi-scale fusion, overcoming the bottlenecks in previous work, where
limited multi-modal information is shared and interacted between feature maps.
In the decoder, we also develop a referring-infused adaptation that provides
explicit referring guidance through the query tokens. The experiments showcase
the superior performance of our model (+3.42%) compared to prior works,
demonstrating the effectiveness of our designs.