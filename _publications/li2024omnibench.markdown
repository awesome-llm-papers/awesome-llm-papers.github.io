---
layout: publication
title: 'Omnibench: Towards The Future Of Universal Omni-language Models'
authors: Yizhi Li, Ge Zhang, Yinghao Ma, Ruibin Yuan, Kang Zhu, Hangyu Guo, Yiming
  Liang, Jiaheng Liu, Jian Yang, Siwei Wu, Xingwei Qu, Jinjie Shi, Xinyue Zhang, Zhenzhu
  Yang, Xiangzhou Wang, Zhaoxiang Zhang, Zachary Liu, Emmanouil Benetos, Wenhao Huang,
  Chenghua Lin
conference: No Venue
year: 2024
bibkey: li2024omnibench
additional_links: [{name: Code, url: 'https://m-a-p.ai/OmniBench'}, {name: Code, url: 'https://huggingface.co/discussions/paper/66f2a7c3707fbf6273d63f33'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2409.15272'}]
tags: ["Datasets", "Evaluation", "Training Techniques"]
short_authors: Li et al.
---
Recent advancements in multimodal large language models (MLLMs) have aimed to integrate and interpret data across diverse modalities. However, the capacity of these models to concurrently process and reason about multiple modalities remains inadequately explored, partly due to the lack of comprehensive modality-wise benchmarks. We introduce OmniBench, a novel benchmark designed to rigorously evaluate models' ability to recognize, interpret, and reason across visual, acoustic, and textual inputs simultaneously. We define models capable of such tri-modal processing as omni-language models (OLMs). OmniBench is distinguished by high-quality human annotations, ensuring that accurate responses require integrated understanding and reasoning across all three modalities. Our main findings reveal that: i) open-source OLMs exhibit critical limitations in instruction-following and reasoning capabilities within tri-modal contexts; and ii) the baseline models perform poorly (below 50% accuracy) even when provided with alternative textual representations of images and audio. These results suggest that the ability to construct a consistent context from text, image, and audio is often overlooked in existing MLLM training paradigms. We advocate for future research to focus on developing more robust tri-modal integration techniques and training strategies to enhance OLM performance across diverse modalities. The codes and live leaderboard could be found at https://m-a-p.ai/OmniBench.

https://huggingface.co/discussions/paper/66f2a7c3707fbf6273d63f33