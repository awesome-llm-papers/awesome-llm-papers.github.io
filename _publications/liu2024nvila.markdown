---
layout: publication
title: 'NVILA: Efficient Frontier Visual Language Models'
authors: Zhijian Liu, Ligeng Zhu, Baifeng Shi, Zhuoyang Zhang, Yuming Lou, Shang Yang,
  Haocheng Xi, Shiyi Cao, Yuxian Gu, Dacheng Li, Xiuyu Li, Yunhao Fang, Yukang Chen,
  Cheng-yu Hsieh, De-an Huang, An-chieh Cheng, Vishwesh Nath, Jinyi Hu, Sifei Liu,
  Ranjay Krishna, Daguang Xu, Xiaolong Wang, Pavlo Molchanov, Jan Kautz, Hongxu Yin,
  Song Han, Yao Lu
conference: No Venue
year: 2024
bibkey: liu2024nvila
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/67530604886878c886844750'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2412.04468'}]
tags: ["Efficiency", "Model Architecture"]
short_authors: Liu et al.
---
Visual language models (VLMs) have made significant advances in accuracy in recent years. However, their efficiency has received much less attention. This paper introduces NVILA, a family of open VLMs designed to optimize both efficiency and accuracy. Building on top of VILA, we improve its model architecture by first scaling up the spatial and temporal resolutions, and then compressing visual tokens. This "scale-then-compress" approach enables NVILA to efficiently process high-resolution images and long videos. We also conduct a systematic investigation to enhance the efficiency of NVILA throughout its entire lifecycle, from training and fine-tuning to deployment. NVILA matches or surpasses the accuracy of many leading open and proprietary VLMs across a wide range of image and video benchmarks. At the same time, it reduces training costs by 4.5X, fine-tuning memory usage by 3.4X, pre-filling latency by 1.6-2.2X, and decoding latency by 1.2-2.8X. We will soon make our code and models available to facilitate reproducibility.

https://huggingface.co/discussions/paper/67530604886878c886844750