---
layout: publication
title: Video Instruction Tuning With Synthetic Data
authors: Yuanhan Zhang, Jinming Wu, Wei Li, Bo Li, Zejun Ma, Ziwei Liu, Chunyuan Li
conference: No Venue
year: 2024
bibkey: zhang2024video
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2410.02713'}]
tags: ["Datasets", "Training Techniques"]
short_authors: Zhang et al.
---
The development of video large multimodal models (LMMs) has been hindered by the difficulty of curating large amounts of high-quality raw data from the web. To address this, we propose an alternative approach by creating a high-quality synthetic dataset specifically for video instruction-following, namely LLaVA-Video-178K. This dataset includes key tasks such as detailed captioning, open-ended question-answering (QA), and multiple-choice QA. By training on this dataset, in combination with existing visual instruction tuning data, we introduce LLaVA-Video, a new video LMM. Our experiments demonstrate that LLaVA-Video achieves strong performance across various video benchmarks, highlighting the effectiveness of our dataset. We plan to release the dataset, its generation pipeline, and the model checkpoints.

https://huggingface.co/discussions/paper/66ff4f625a359c1af116974f