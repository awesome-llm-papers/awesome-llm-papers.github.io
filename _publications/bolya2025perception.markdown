---
layout: publication
title: 'Perception Encoder: The Best Visual Embeddings Are Not At The Output Of The
  Network'
authors: "Daniel Bolya, Po-yao Huang, Peize Sun, Jang Hyun Cho, Andrea Madotto, Chen\
  \ Wei, Tengyu Ma, Jiale Zhi, Jathushan Rajasegaran, Hanoona Rasheed, Junke Wang,\
  \ Marco Monteiro, Hu Xu, Shiyu Dong, Nikhila Ravi, Daniel Li, Piotr Doll\xE1r, Christoph\
  \ Feichtenhofer"
conference: No Venue
year: 2025
bibkey: bolya2025perception
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/680237b12724430ec1defdfa'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2504.13181'}]
tags: ["Datasets", "Training Techniques"]
short_authors: Bolya et al.
---
We introduce Perception Encoder (PE), a state-of-the-art encoder for image and video understanding trained via simple vision-language learning. Traditionally, vision encoders have relied on a variety of pretraining objectives, each tailored to specific downstream tasks such as classification, captioning, or localization. Surprisingly, after scaling our carefully tuned image pretraining recipe and refining with our robust video data engine, we find that contrastive vision-language training alone can produce strong, general embeddings for all of these downstream tasks. There is only one caveat: these embeddings are hidden within the intermediate layers of the network. To draw them out, we introduce two alignment methods, language alignment for multimodal language modeling, and spatial alignment for dense prediction. Together with the core contrastive checkpoint, our PE family of models achieves state-of-the-art performance on a wide variety of tasks, including zero-shot image and video classification and retrieval; document, image, and video Q&A; and spatial tasks such as detection, depth estimation, and tracking. To foster further research, we are releasing our models, code, and a novel dataset of synthetically and human-annotated videos.

https://huggingface.co/discussions/paper/680237b12724430ec1defdfa