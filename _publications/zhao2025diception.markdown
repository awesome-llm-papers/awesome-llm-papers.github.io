---
layout: publication
title: 'DICEPTION: A Generalist Diffusion Model For Visual Perceptual Tasks'
authors: Canyu Zhao, Mingyu Liu, Huanyi Zheng, Muzhi Zhu, Zhiyue Zhao, Hao Chen, Tong
  He, Chunhua Shen
conference: No Venue
year: 2025
bibkey: zhao2025diception
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2502.17157'}]
tags: ["Evaluation", "Fine-Tuning", "Training Techniques"]
short_authors: Zhao et al.
---
Our primary goal here is to create a good, generalist perception model that can tackle multiple tasks, within limits on computational resources and training data. To achieve this, we resort to text-to-image diffusion models pre-trained on billions of images. Our exhaustive evaluation metrics demonstrate that DICEPTION effectively tackles multiple perception tasks, achieving performance on par with state-of-the-art models. We achieve results on par with SAM-vit-h using only 0.06% of their data (e.g., 600K vs. 1B pixel-level annotated images). Inspired by Wang et al., DICEPTION formulates the outputs of various perception tasks using color encoding; and we show that the strategy of assigning random colors to different instances is highly effective in both entity segmentation and semantic segmentation. Unifying various perception tasks as conditional image generation enables us to fully leverage pre-trained text-to-image models. Thus, DICEPTION can be efficiently trained at a cost of orders of magnitude lower, compared to conventional models that were trained from scratch. When adapting our model to other tasks, it only requires fine-tuning on as few as 50 images and 1% of its parameters. DICEPTION provides valuable insights and a more promising solution for visual generalist models.

https://huggingface.co/discussions/paper/67bd328aac4a596a43b532ae