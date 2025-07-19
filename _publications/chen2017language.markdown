---
layout: publication
title: Language-based Image Editing With Recurrent Attentive Models
authors: Chen et al.
conference: 2018 IEEE/CVF Conference on Computer Vision and Pattern Recognition
year: 2017
bibkey: chen2017language
citations: 125
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1711.06288'}]
tags: [Tools, CVPR, Datasets]
---
We investigate the problem of Language-Based Image Editing (LBIE). Given a
source image and a natural language description, we want to generate a target
image by editing the source image based on the description. We propose a
generic modeling framework for two sub-tasks of LBIE: language-based image
segmentation and image colorization. The framework uses recurrent attentive
models to fuse image and language features. Instead of using a fixed step size,
we introduce for each region of the image a termination gate to dynamically
determine after each inference step whether to continue extrapolating
additional information from the textual description. The effectiveness of the
framework is validated on three datasets. First, we introduce a synthetic
dataset, called CoSaL, to evaluate the end-to-end performance of our LBIE
system. Second, we show that the framework leads to state-of-the-art
performance on image segmentation on the ReferIt dataset. Third, we present the
first language-based colorization result on the Oxford-102 Flowers dataset.