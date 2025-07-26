---
layout: publication
title: 'Spatialvlm: Endowing Vision-language Models With Spatial Reasoning Capabilities'
authors: Boyuan Chen, Zhuo Xu, Sean Kirmani, Brian Ichter, Danny Driess, Pete Florence,
  Dorsa Sadigh, Leonidas Guibas, Fei Xia
conference: No Venue
year: 2024
bibkey: chen2024spatialvlm
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2401.12168'}]
tags: ["Applications", "Model Architecture"]
short_authors: Chen et al.
---
Understanding and reasoning about spatial relationships is a fundamental capability for Visual Question Answering (VQA) and robotics. While Vision Language Models (VLM) have demonstrated remarkable performance in certain VQA benchmarks, they still lack capabilities in 3D spatial reasoning, such as recognizing quantitative relationships of physical objects like distances or size differences. We hypothesize that VLMs' limited spatial reasoning capability is due to the lack of 3D spatial knowledge in training data and aim to solve this problem by training VLMs with Internet-scale spatial reasoning data. To this end, we present a system to facilitate this approach. We first develop an automatic 3D spatial VQA data generation framework that scales up to 2 billion VQA examples on 10 million real-world images. We then investigate various factors in the training recipe, including data quality, training pipeline, and VLM architecture. Our work features the first internet-scale 3D spatial reasoning dataset in metric space. By training a VLM on such data, we significantly enhance its ability on both qualitative and quantitative spatial VQA. Finally, we demonstrate that this VLM unlocks novel downstream applications in chain-of-thought spatial reasoning and robotics due to its quantitative estimation capability. Project website: https://spatial-vlm.github.io/

https://huggingface.co/discussions/paper/65af3b821f418c7449386e64