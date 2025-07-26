---
layout: publication
title: 'Comat: Aligning Text-to-image Diffusion Model With Image-to-text Concept Matching'
authors: Dongzhi Jiang, Guanglu Song, Xiaoshi Wu, Renrui Zhang, Dazhong Shen, Zhuofan
  Zong, Yu Liu, Hongsheng Li
conference: No Venue
year: 2024
bibkey: jiang2024comat
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2404.03653'}]
tags: ["Fine-Tuning", "Training Techniques"]
short_authors: Jiang et al.
---
Diffusion models have demonstrated great success in the field of text-to-image generation. However, alleviating the misalignment between the text prompts and images is still challenging. The root reason behind the misalignment has not been extensively investigated. We observe that the misalignment is caused by inadequate token attention activation. We further attribute this phenomenon to the diffusion model's insufficient condition utilization, which is caused by its training paradigm. To address the issue, we propose CoMat, an end-to-end diffusion model fine-tuning strategy with an image-to-text concept matching mechanism. We leverage an image captioning model to measure image-to-text alignment and guide the diffusion model to revisit ignored tokens. A novel attribute concentration module is also proposed to address the attribute binding problem. Without any image or human preference data, we use only 20K text prompts to fine-tune SDXL to obtain CoMat-SDXL. Extensive experiments show that CoMat-SDXL significantly outperforms the baseline model SDXL in two text-to-image alignment benchmarks and achieves start-of-the-art performance.

https://huggingface.co/discussions/paper/660f613259d8544c00e52f21