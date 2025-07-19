---
layout: publication
title: 'Falcon: A Remote Sensing Vision-language Foundation Model'
authors: Yao et al.
conference: IEEE Transactions on Geoscience and Remote Sensing
year: 2025
bibkey: yao2025falcon
citations: 96
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2503.11070'}]
tags: [Training Techniques, Prompting, Fine Tuning, Multimodal Models, Datasets]
---
This paper introduces a holistic vision-language foundation model tailored
for remote sensing, named Falcon. Falcon offers a unified, prompt-based
paradigm that effectively executes comprehensive and complex remote sensing
tasks. Falcon demonstrates powerful understanding and reasoning abilities at
the image, region, and pixel levels. Specifically, given simple natural
language instructions and remote sensing images, Falcon can produce impressive
results in text form across 14 distinct tasks, i.e., image classification,
object detection, segmentation, image captioning, and etc. To facilitate
Falcon's training and empower its representation capacity to encode rich
spatial and semantic information, we developed Falcon_SFT, a large-scale,
multi-task, instruction-tuning dataset in the field of remote sensing. The
Falcon_SFT dataset consists of approximately 78 million high-quality data
samples, covering 5.6 million multi-spatial resolution and multi-view remote
sensing images with diverse instructions. It features hierarchical annotations
and undergoes manual sampling verification to ensure high data quality and
reliability. Extensive comparative experiments are conducted, which verify that
Falcon achieves remarkable performance over 67 datasets and 14 tasks, despite
having only 0.7B parameters. We release the complete dataset, code, and model
weights at https://github.com/TianHuiLab/Falcon, hoping to help further develop
the open-source community.