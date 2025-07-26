---
layout: publication
title: 'Migician: Revealing The Magic Of Free-form Multi-image Grounding In Multimodal
  Large Language Models'
authors: You Li, Heyu Huang, Chi Chen, Kaiyu Huang, Chao Huang, Zonghao Guo, Zhiyuan
  Liu, Jinan Xu, Yuhua Li, Ruixuan Li, Maosong Sun
conference: No Venue
year: 2025
bibkey: li2025migician
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/67850073609833baf1d0c9b2'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2501.05767'}]
tags: ["Datasets", "Evaluation", "Prompting", "Tools"]
short_authors: Li et al.
---
The recent advancement of Multimodal Large Language Models (MLLMs) has significantly improved their fine-grained perception of single images and general comprehension across multiple images. However, existing MLLMs still face challenges in achieving precise grounding in complex multi-image scenarios. To address this, we first explore a Chain-of-Thought (CoT) framework that integrates single-image grounding with multi-image comprehension. While partially effective, it remains unstable and struggles to capture abstract visual information due to its non-end-to-end nature. Therefore, we introduce Migician, the first multi-image grounding model capable of performing free-form and accurate grounding across multiple images. To support this, we present the MGrounding-630k dataset, which comprises data for several multi-image grounding tasks derived from existing datasets, along with newly generated free-form grounding instruction-following data. Furthermore, we propose MIG-Bench, a comprehensive benchmark specifically designed for evaluating multi-image grounding capabilities. Experimental results demonstrate that our model achieves significantly superior multi-image grounding capabilities, outperforming the best existing MLLMs by 21.61% and even surpassing much larger 70B models. Our code, model, dataset, and benchmark are fully open-sourced.

https://huggingface.co/discussions/paper/67850073609833baf1d0c9b2