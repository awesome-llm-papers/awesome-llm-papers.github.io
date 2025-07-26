---
layout: publication
title: 'Llamax: Scaling Linguistic Horizons Of LLM By Enhancing Translation Capabilities
  Beyond 100 Languages'
authors: Yinquan Lu, Wenhao Zhu, Lei Li, Yu Qiao, Fei Yuan
conference: No Venue
year: 2024
bibkey: lu2024llamax
additional_links: [{name: Code, url: 'https://github.com/CONE-MT/LLaMAX/'}, {name: Code,
    url: 'https://huggingface.co/LLaMAX/'}, {name: Code, url: 'https://huggingface.co/discussions/paper/668cab03a249df5a139d0f31'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2407.05975'}]
tags: ["Training Techniques"]
short_authors: Lu et al.
---
Large Language Models~(LLMs) demonstrate remarkable translation capabilities in high-resource language tasks, yet their performance in low-resource languages is hindered by insufficient multilingual data during pre-training. To address this, we dedicate 35,000 A100-SXM4-80GB GPU hours in conducting extensive multilingual continual pre-training on the LLaMA series models, enabling translation support across more than 100 languages. Through a comprehensive analysis of training strategies, such as vocabulary expansion and data augmentation, we develop LLaMAX. Remarkably, without sacrificing its generalization ability, LLaMAX achieves significantly higher translation performance compared to existing open-source LLMs~(by more than 10 spBLEU points) and performs on-par with specialized translation model~(M2M-100-12B) on the Flores-101 benchmark. Extensive experiments indicate that LLaMAX can serve as a robust multilingual foundation model. The code~https://github.com/CONE-MT/LLaMAX/. and models~https://huggingface.co/LLaMAX/. are publicly available.

https://huggingface.co/discussions/paper/668cab03a249df5a139d0f31