---
layout: publication
title: Large-scale Pre-training For Grounded Video Caption Generation
authors: Kazakos Evangelos, Schmid Cordelia, Sivic Josef
conference: 2019 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2025
bibkey: kazakos2025large
citations: 165
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2503.10781'}]
tags: [Training Techniques, CVPR, Fine Tuning, Datasets]
---
We propose a novel approach for captioning and object grounding in video,
where the objects in the caption are grounded in the video via temporally dense
bounding boxes. We introduce the following contributions. First, we present a
large-scale automatic annotation method that aggregates captions grounded with
bounding boxes across individual frames into temporally dense and consistent
bounding box annotations. We apply this approach on the HowTo100M dataset to
construct a large-scale pre-training dataset, named HowToGround1M. We also
introduce a Grounded Video Caption Generation model, dubbed GROVE, and
pre-train the model on HowToGround1M. Second, we introduce a new dataset,
called iGround, of 3500 videos with manually annotated captions and dense
spatio-temporally grounded bounding boxes. This allows us to measure progress
on this challenging problem, as well as to fine-tune our model on this
small-scale but high-quality data. Third, we demonstrate that our approach
achieves state-of-the-art results on the proposed iGround dataset compared to a
number of baselines, as well as on the VidSTG and ActivityNet-Entities
datasets. We perform extensive ablations that demonstrate the importance of
pre-training using our automatically annotated HowToGround1M dataset followed
by fine-tuning on the manually annotated iGround dataset and validate the key
technical contributions of our model.