---
layout: publication
title: 'Cogvideox: Text-to-video Diffusion Models With An Expert Transformer'
authors: Zhuoyi Yang, Jiayan Teng, Wendi Zheng, Ming Ding, Shiyu Huang, Jiazheng Xu,
  Yuanming Yang, Wenyi Hong, Xiaohan Zhang, Guanyu Feng, da Yin, Xiaotao Gu, Yuxuan
  Zhang, Weihan Wang, Yean Cheng, Ting Liu, Bin Xu, Yuxiao Dong, Jie Tang
conference: No Venue
year: 2024
bibkey: yang2024cogvideox
additional_links: [{name: Code, url: 'https://github.com/THUDM/CogVideo'}, {name: Code,
    url: 'https://huggingface.co/discussions/paper/66bacf5dc9b2ab14b398f85c'}, {name: Paper,
    url: 'https://arxiv.org/abs/hf2408.06072'}]
tags: ["Model Architecture", "Training Techniques"]
short_authors: Yang et al.
---
We introduce CogVideoX, a large-scale diffusion transformer model designed for generating videos based on text prompts. To efficently model video data, we propose to levearge a 3D Variational Autoencoder (VAE) to compress videos along both spatial and temporal dimensions. To improve the text-video alignment, we propose an expert transformer with the expert adaptive LayerNorm to facilitate the deep fusion between the two modalities. By employing a progressive training technique, CogVideoX is adept at producing coherent, long-duration videos characterized by significant motions. In addition, we develop an effective text-video data processing pipeline that includes various data preprocessing strategies and a video captioning method. It significantly helps enhance the performance of CogVideoX, improving both generation quality and semantic alignment. Results show that CogVideoX demonstrates state-of-the-art performance across both multiple machine metrics and human evaluations. The model weights of both the 3D Causal VAE and CogVideoX are publicly available at https://github.com/THUDM/CogVideo.

https://huggingface.co/discussions/paper/66bacf5dc9b2ab14b398f85c