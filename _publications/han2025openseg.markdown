---
layout: publication
title: 'Openseg-r: Improving Open-vocabulary Segmentation Via Step-by-step Visual
  Reasoning'
authors: Han et al.
conference: Proceedings of the 57th Annual Meeting of the Association for Computational
  Linguistics
year: 2025
bibkey: han2025openseg
citations: 57
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2505.16974'}]
tags: [Model Architecture, Prompting, Tools, Interpretability And Explainability,
  Evaluation, ACL, RAG, Multimodal Models, Datasets, Reinforcement Learning, Attention
    Mechanism]
---
Open-Vocabulary Segmentation (OVS) has drawn increasing attention for its capacity to generalize segmentation beyond predefined categories. However, existing methods typically predict segmentation masks with simple forward inference, lacking explicit reasoning and interpretability. This makes it challenging for OVS model to distinguish similar categories in open-world settings due to the lack of contextual understanding and discriminative visual cues. To address this limitation, we propose a step-by-step visual reasoning framework for open-vocabulary segmentation, named OpenSeg-R. The proposed OpenSeg-R leverages Large Multimodal Models (LMMs) to perform hierarchical visual reasoning before segmentation. Specifically, we generate both generic and image-specific reasoning for each image, forming structured triplets that explain the visual reason for objects in a coarse-to-fine manner. Based on these reasoning steps, we can compose detailed description prompts, and feed them to the segmentor to produce more accurate segmentation masks. To the best of our knowledge, OpenSeg-R is the first framework to introduce explicit step-by-step visual reasoning into OVS. Experimental results demonstrate that OpenSeg-R significantly outperforms state-of-the-art methods on open-vocabulary semantic segmentation across five benchmark datasets. Moreover, it achieves consistent gains across all metrics on open-vocabulary panoptic segmentation. Qualitative results further highlight the effectiveness of our reasoning-guided framework in improving both segmentation precision and interpretability. Our code is publicly available at https://github.com/Hanzy1996/OpenSeg-R.