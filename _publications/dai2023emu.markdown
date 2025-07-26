---
layout: publication
title: 'Emu: Enhancing Image Generation Models Using Photogenic Needles In A Haystack'
authors: Xiaoliang Dai, Ji Hou, Chih-yao Ma, Sam Tsai, Jialiang Wang, Rui Wang, Peizhao
  Zhang, Simon Vandenhende, Xiaofang Wang, Abhimanyu Dubey, Matthew Yu, Abhishek Kadian,
  Filip Radenovic, Dhruv Mahajan, Kunpeng Li, Yue Zhao, Vladan Petrovic, Mitesh Kumar
  Singh, Simran Motwani, Yi Wen, Yiwen Song, Roshan Sumbaly, Vignesh Ramanathan, Zijian
  He, Peter Vajda, Devi Parikh
conference: No Venue
year: 2023
bibkey: dai2023emu
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2309.15807'}]
tags: ["Evaluation", "Fine-Tuning", "Model Architecture", "Training Techniques"]
short_authors: Dai et al.
---
Training text-to-image models with web scale image-text pairs enables the generation of a wide range of visual concepts from text. However, these pre-trained models often face challenges when it comes to generating highly aesthetic images. This creates the need for aesthetic alignment post pre-training. In this paper, we propose quality-tuning to effectively guide a pre-trained model to exclusively generate highly visually appealing images, while maintaining generality across visual concepts. Our key insight is that supervised fine-tuning with a set of surprisingly small but extremely visually appealing images can significantly improve the generation quality. We pre-train a latent diffusion model on 1.1 billion image-text pairs and fine-tune it with only a few thousand carefully selected high-quality images. The resulting model, Emu, achieves a win rate of 82.9% compared with its pre-trained only counterpart. Compared to the state-of-the-art SDXLv1.0, Emu is preferred 68.4% and 71.3% of the time on visual appeal on the standard PartiPrompts and our Open User Input benchmark based on the real-world usage of text-to-image models. In addition, we show that quality-tuning is a generic approach that is also effective for other architectures, including pixel diffusion and masked generative transformer models.

https://huggingface.co/discussions/paper/6515031d4b4f53b8268ac72f