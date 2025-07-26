---
layout: publication
title: 'Vl-adapter: Parameter-efficient Transfer Learning For Vision-and-language
  Tasks'
authors: Yi-lin Sung, Jaemin Cho, Mohit Bansal
conference: 2022 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2022
bibkey: sung2021vl
citations: 185
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2112.06825'}]
tags: ["CVPR", "Fine-Tuning", "Training Techniques"]
short_authors: Yi-lin Sung, Jaemin Cho, Mohit Bansal
---
Recently, fine-tuning language models pre-trained on large text corpora have
provided huge improvements on vision-and-language (V&L) tasks as well as on
pure language tasks. However, fine-tuning the entire parameter set of
pre-trained models becomes impractical since the model size is growing rapidly.
Hence, in this paper, we introduce adapter-based parameter-efficient transfer
learning techniques to V&L models such as VL-BART and VLT5. We evaluate our
methods in a unified multi-task setup on both image-text and video-text
benchmarks. For the image-text tasks, we use four diverse V&L datasets: VQAv2,
GQA, NLVR2 , and MSCOCO image captioning. For video-text tasks, we use TVQA,
How2QA, TVC, and YC2C. With careful training and thorough experiments, we
benchmark three popular adapter-based methods (Adapter, Hyperformer, Compacter)
against the standard full fine-tuning and the recently proposed prompt-tuning
approach. We also enhance the efficiency and performance of adapters by sharing
their weights to attain knowledge across tasks. Our results demonstrate that
training the adapter with the weight-sharing technique (4.18% of total
parameters for image-text tasks and 3.39% for video-text tasks) can match the
performance of fine-tuning the entire model. Lastly, we present a comprehensive
analysis including the combination of adapter and task-specific prompts and the
impact of V&L pre-training on adapters. Our code is available at:
https://github.com/ylsung/VL_adapter.