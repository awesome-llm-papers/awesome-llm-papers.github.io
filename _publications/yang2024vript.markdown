---
layout: publication
title: 'Vript: A Video Is Worth Thousands Of Words'
authors: Dongjie Yang, Suyuan Huang, Chengqiang Lu, Xiaodong Han, Haoxin Zhang, Yan
  Gao, Yao Hu, Hai Zhao
conference: No Venue
year: 2024
bibkey: yang2024vript
additional_links: [{name: Code, url: 'https://github.com/mutonix/Vript'}, {name: Code,
    url: 'https://huggingface.co/discussions/paper/6667ce1cf3e4efa2764a9fb5'}, {name: Paper,
    url: 'https://arxiv.org/abs/hf2406.06040'}]
tags: ["Datasets", "Evaluation", "Has Code", "Model Architecture", "Training Techniques"]
short_authors: Yang et al.
---
Advancements in multimodal learning, particularly in video understanding and generation, require high-quality video-text datasets for improved model performance. Vript addresses this issue with a meticulously annotated corpus of 12K high-resolution videos, offering detailed, dense, and script-like captions for over 420K clips. Each clip has a caption of ~145 words, which is over 10x longer than most video-text datasets. Unlike captions only documenting static content in previous datasets, we enhance video captioning to video scripting by documenting not just the content, but also the camera operations, which include the shot types (medium shot, close-up, etc) and camera movements (panning, tilting, etc). By utilizing the Vript, we explore three training paradigms of aligning more text with the video modality rather than clip-caption pairs. This results in Vriptor, a top-performing video captioning model among open-source models, comparable to GPT-4V in performance. Vriptor is also a powerful model capable of end-to-end generation of dense and detailed captions for long videos. Moreover, we introduce Vript-Hard, a benchmark consisting of three video understanding tasks that are more challenging than existing benchmarks: Vript-HAL is the first benchmark evaluating action and object hallucinations in video LLMs, Vript-RR combines reasoning with retrieval resolving question ambiguity in long-video QAs, and Vript-ERO is a new task to evaluate the temporal understanding of events in long videos rather than actions in short videos in previous works. All code, models, and datasets are available in https://github.com/mutonix/Vript.

https://huggingface.co/discussions/paper/6667ce1cf3e4efa2764a9fb5