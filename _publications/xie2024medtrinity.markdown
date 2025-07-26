---
layout: publication
title: 'Medtrinity-25m: A Large-scale Multimodal Dataset With Multigranular Annotations
  For Medicine'
authors: Yunfei Xie, Ce Zhou, Lang Gao, Juncheng Wu, Xianhang Li, Hong-yu Zhou, Sheng
  Liu, Lei Xing, James Zou, Cihang Xie, Yuyin Zhou
conference: No Venue
year: 2024
bibkey: xie2024medtrinity
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/66b2d7e9fa7069c7f1f088d7'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2408.02900'}]
tags: ["Datasets"]
short_authors: Xie et al.
---
This paper introduces MedTrinity-25M, a comprehensive, large-scale multimodal dataset for medicine, covering over 25 million images across 10 modalities, with multigranular annotations for more than 65 diseases. These enriched annotations encompass both global textual information, such as disease/lesion type, modality, region-specific descriptions, and inter-regional relationships, as well as detailed local annotations for regions of interest (ROIs), including bounding boxes, segmentation masks. Unlike existing approach which is limited by the availability of image-text pairs, we have developed the first automated pipeline that scales up multimodal data by generating multigranular visual and texual annotations (in the form of image-ROI-description triplets) without the need for any paired text descriptions. Specifically, data from over 90 different sources have been collected, preprocessed, and grounded using domain-specific expert models to identify ROIs related to abnormal regions. We then build a comprehensive knowledge base and prompt multimodal large language models to perform retrieval-augmented generation with the identified ROIs as guidance, resulting in multigranular texual descriptions. Compared to existing datasets, MedTrinity-25M provides the most enriched annotations, supporting a comprehensive range of multimodal tasks such as captioning and report generation, as well as vision-centric tasks like classification and segmentation. Pretraining on MedTrinity-25M, our model achieves state-of-the-art performance on VQA-RAD and PathVQA, surpassing both multimodal large language models and other representative SoTA approaches. This dataset can also be utilized to support large-scale pre-training of multimodal medical AI models, contributing to the development of future foundation models in the medical domain.

https://huggingface.co/discussions/paper/66b2d7e9fa7069c7f1f088d7