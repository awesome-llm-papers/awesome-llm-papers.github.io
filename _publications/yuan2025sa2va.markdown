---
layout: publication
title: 'Sa2va: Marrying SAM2 With Llava For Dense Grounded Understanding Of Images
  And Videos'
authors: Haobo Yuan, Xiangtai Li, Tao Zhang, Zilong Huang, Shilin Xu, Shunping Ji,
  Yunhai Tong, Lu Qi, Jiashi Feng, Ming-hsuan Yang
conference: No Venue
year: 2025
bibkey: yuan2025sa2va
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2501.04001'}]
tags: ["Applications"]
short_authors: Yuan et al.
---
This work presents Sa2VA, the first unified model for dense grounded understanding of both images and videos. Unlike existing multi-modal large language models, which are often limited to specific modalities and tasks, Sa2VA supports a wide range of image and video tasks, including referring segmentation and conversation, with minimal one-shot instruction tuning. Sa2VA combines SAM-2, a foundation video segmentation model, with LLaVA, an advanced vision-language model, and unifies text, image, and video into a shared LLM token space. Using the LLM, Sa2VA generates instruction tokens that guide SAM-2 in producing precise masks, enabling a grounded, multi-modal understanding of both static and dynamic visual content. Additionally, we introduce Ref-SAV, an auto-labeled dataset containing over 72k object expressions in complex video scenes, designed to boost model performance. We also manually validate 2k video objects in the Ref-SAV datasets to benchmark referring video object segmentation in complex environments. Experiments show that Sa2VA achieves state-of-the-art across multiple tasks, particularly in referring video object segmentation, highlighting its potential for complex real-world applications.

https://huggingface.co/discussions/paper/677e2056dbff7b495e85ede6