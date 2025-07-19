---
layout: publication
title: Object-aware Video-language Pre-training For Retrieval
authors: Wang et al.
conference: 2022 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2021
bibkey: wang2021object
citations: 57
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2112.00656'}]
tags: [RAG, Training Techniques, CVPR, Evaluation, Transformer, Model Architecture,
  Datasets]
---
Recently, by introducing large-scale dataset and strong transformer network,
video-language pre-training has shown great success especially for retrieval.
Yet, existing video-language transformer models do not explicitly fine-grained
semantic align. In this work, we present Object-aware Transformers, an
object-centric approach that extends video-language transformer to incorporate
object representations. The key idea is to leverage the bounding boxes and
object tags to guide the training process. We evaluate our model on three
standard sub-tasks of video-text matching on four widely used benchmarks. We
also provide deep analysis and detailed ablation about the proposed method. We
show clear improvement in performance across all tasks and datasets considered,
demonstrating the value of a model that incorporates object representations
into a video-language architecture. The code will be released at
https://github.com/FingerRec/OA-Transformer.