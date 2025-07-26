---
layout: publication
title: 'Coconut: Modernizing COCO Segmentation'
authors: Xueqing Deng, Qihang Yu, Peng Wang, Xiaohui Shen, Liang-chieh Chen
conference: No Venue
year: 2024
bibkey: deng2024coconut
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2404.08639'}]
tags: ["Datasets"]
short_authors: Deng et al.
---
In recent decades, the vision community has witnessed remarkable progress in visual recognition, partially owing to advancements in dataset benchmarks. Notably, the established COCO benchmark has propelled the development of modern detection and segmentation systems. However, the COCO segmentation benchmark has seen comparatively slow improvement over the last decade. Originally equipped with coarse polygon annotations for thing instances, it gradually incorporated coarse superpixel annotations for stuff regions, which were subsequently heuristically amalgamated to yield panoptic segmentation annotations. These annotations, executed by different groups of raters, have resulted not only in coarse segmentation masks but also in inconsistencies between segmentation types. In this study, we undertake a comprehensive reevaluation of the COCO segmentation annotations. By enhancing the annotation quality and expanding the dataset to encompass 383K images with more than 5.18M panoptic masks, we introduce COCONut, the COCO Next Universal segmenTation dataset. COCONut harmonizes segmentation annotations across semantic, instance, and panoptic segmentation with meticulously crafted high-quality masks, and establishes a robust benchmark for all segmentation tasks. To our knowledge, COCONut stands as the inaugural large-scale universal segmentation dataset, verified by human raters. We anticipate that the release of COCONut will significantly contribute to the community's ability to assess the progress of novel neural networks.

https://huggingface.co/discussions/paper/661c8a497a16dc848a269734