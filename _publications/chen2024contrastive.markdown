---
layout: publication
title: Contrastive Localized Language-image Pre-training
authors: Hong-you Chen, Zhengfeng Lai, Haotian Zhang, Xinze Wang, Marcin Eichner,
  Keen You, Meng Cao, Bowen Zhang, Yinfei Yang, Zhe Gan
conference: No Venue
year: 2024
bibkey: chen2024contrastive
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/66ff590c39485e454983f258'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2410.02746'}]
tags: ["Applications", "Training Techniques"]
short_authors: Chen et al.
---
Contrastive Language-Image Pre-training (CLIP) has been a celebrated method for training vision encoders to generate image/text representations facilitating various applications. Recently, CLIP has been widely adopted as the vision backbone of multimodal large language models (MLLMs) to connect image inputs for language interactions. The success of CLIP as a vision-language foundation model relies on aligning web-crawled noisy text annotations at image levels. Nevertheless, such criteria may become insufficient for downstream tasks in need of fine-grained vision representations, especially when region-level understanding is demanding for MLLMs. In this paper, we improve the localization capability of CLIP with several advances. We propose a pre-training method called Contrastive Localized Language-Image Pre-training (CLOC) by complementing CLIP with region-text contrastive loss and modules. We formulate a new concept, promptable embeddings, of which the encoder produces image embeddings easy to transform into region representations given spatial hints. To support large-scale pre-training, we design a visually-enriched and spatially-localized captioning framework to effectively generate region-text pseudo-labels at scale. By scaling up to billions of annotated images, CLOC enables high-quality regional embeddings for image region recognition and retrieval tasks, and can be a drop-in replacement of CLIP to enhance MLLMs, especially on referring and grounding tasks.

https://huggingface.co/discussions/paper/66ff590c39485e454983f258