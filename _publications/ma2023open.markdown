---
layout: publication
title: 'Lampilot: An Open Benchmark Dataset For Autonomous Driving With Language Model
  Programs'
authors: Yunsheng Ma et al.
conference: 2024 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2023
citations: 15
bibkey: ma2023open
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2312.04372'}, {name: Code,
    url: 'https://github.com/PurdueDigitalTwin/LaMPilot'}]
tags: [Tools, Has Code, RAG, Evaluation]
---
Autonomous driving (AD) has made significant strides in recent years.
However, existing frameworks struggle to interpret and execute spontaneous user
instructions, such as "overtake the car ahead." Large Language Models (LLMs)
have demonstrated impressive reasoning capabilities showing potential to bridge
this gap. In this paper, we present LaMPilot, a novel framework that integrates
LLMs into AD systems, enabling them to follow user instructions by generating
code that leverages established functional primitives. We also introduce
LaMPilot-Bench, the first benchmark dataset specifically designed to
quantitatively evaluate the efficacy of language model programs in AD. Adopting
the LaMPilot framework, we conduct extensive experiments to assess the
performance of off-the-shelf LLMs on LaMPilot-Bench. Our results demonstrate
the potential of LLMs in handling diverse driving scenarios and following user
instructions in driving. To facilitate further research in this area, we
release our code and data at https://github.com/PurdueDigitalTwin/LaMPilot.