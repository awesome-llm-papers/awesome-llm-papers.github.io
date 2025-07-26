---
layout: publication
title: 'Smolvla: A Vision-language-action Model For Affordable And Efficient Robotics'
authors: Mustafa Shukor, Dana Aubakirova, Francesco Capuano, Pepijn Kooijmans, Steven
  Palma, Adil Zouitine, Michel Aractingi, Caroline Pascal, Martino Russi, Andres Marafioti,
  Simon Alibert, Matthieu Cord, Thomas Wolf, Remi Cadene
conference: No Venue
year: 2025
bibkey: shukor2025smolvla
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/683eb85925fcc99d2a7fc2dc'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2506.01844'}]
tags: ["Datasets", "Training Techniques"]
short_authors: Shukor et al.
---
Vision-language models (VLMs) pretrained on large-scale multimodal datasets encode rich visual and linguistic knowledge, making them a strong foundation for robotics. Rather than training robotic policies from scratch, recent approaches adapt VLMs into vision-language-action (VLA) models that enable natural language-driven perception and control. However, existing VLAs are typically massive--often with billions of parameters--leading to high training costs and limited real-world deployability. Moreover, they rely on academic and industrial datasets, overlooking the growing availability of community-collected data from affordable robotic platforms. In this work, we present SmolVLA, a small, efficient, and community-driven VLA that drastically reduces both training and inference costs, while retaining competitive performance. SmolVLA is designed to be trained on a single GPU and deployed on consumer-grade GPUs or even CPUs. To further improve responsiveness, we introduce an asynchronous inference stack decoupling perception and action prediction from action execution, allowing higher control rates with chunked action generation. Despite its compact size, SmolVLA achieves performance comparable to VLAs that are 10x larger. We evaluate SmolVLA on a range of both simulated as well as real-world robotic benchmarks and release all code, pretrained models, and training data.

https://huggingface.co/discussions/paper/683eb85925fcc99d2a7fc2dc