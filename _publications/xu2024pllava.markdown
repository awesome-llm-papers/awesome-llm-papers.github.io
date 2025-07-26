---
layout: publication
title: 'Pllava : Parameter-free Llava Extension From Images To Videos For Video Dense
  Captioning'
authors: Lin Xu, Yilin Zhao, Daquan Zhou, Zhijie Lin, See Kiong Ng, Jiashi Feng
conference: No Venue
year: 2024
bibkey: xu2024pllava
additional_links: [{name: Code, url: 'https://github.com/magic-research/PLLaVA'},
  {name: Code, url: 'https://huggingface.co/discussions/paper/662ef3e8b10f82aa4fabd82c'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2404.16994'}]
tags: ["Applications"]
short_authors: Xu et al.
---
Vision-language pre-training has significantly elevated performance across a wide range of image-language applications. Yet, the pre-training process for video-related tasks demands exceptionally large computational and data resources, which hinders the progress of video-language models. This paper investigates a straightforward, highly efficient, and resource-light approach to adapting an existing image-language pre-trained model for dense video understanding. Our preliminary experiments reveal that directly fine-tuning pre-trained image-language models with multiple frames as inputs on video datasets leads to performance saturation or even a drop. Our further investigation reveals that it is largely attributed to the bias of learned high-norm visual features. Motivated by this finding, we propose a simple but effective pooling strategy to smooth the feature distribution along the temporal dimension and thus reduce the dominant impacts from the extreme features. The new model is termed Pooling LLaVA, or in short. achieves new state-of-the-art performance on modern benchmark datasets for both video question-answer and captioning tasks. Notably, on the recent popular Video ChatGPT benchmark, PLLaVA achieves a score of 3.48 out of 5 on average of five evaluated dimensions, exceeding the previous SOTA results from GPT4V (IG-VLM) by 9%. On the latest multi-choice benchmark MVBench, PLLaVA achieves 58.1% accuracy on average across 20 sub-tasks, 14.5% higher than GPT4V (IG-VLM). Code is available at https://github.com/magic-research/PLLaVA.

https://huggingface.co/discussions/paper/662ef3e8b10f82aa4fabd82c