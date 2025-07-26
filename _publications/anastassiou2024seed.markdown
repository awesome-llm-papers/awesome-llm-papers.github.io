---
layout: publication
title: 'Seed-tts: A Family Of High-quality Versatile Speech Generation Models'
authors: Philip Anastassiou, Jiawei Chen, Jitong Chen, Yuanzhe Chen, Zhuo Chen, Ziyi
  Chen, Jian Cong, Lelai Deng, Chuang Ding, Lu Gao, Mingqing Gong, Peisong Huang,
  Qingqing Huang, Zhiying Huang, Yuanyuan Huo, Dongya Jia, Chumin Li, Feiya Li, Hui
  Li, Jiaxin Li, Xiaoyang Li, Xingxing Li, Lin Liu, Shouda Liu, Sichao Liu, Xudong
  Liu, Yuchen Liu, Zhengxi Liu, Lu Lu, Junjie Pan, Xin Wang, Yuping Wang, Yuxuan Wang,
  Zhen Wei, Jian Wu, Chao Yao, Yifeng Yang, Yuanhao Yi, Junteng Zhang, Qidi Zhang,
  Shuo Zhang, Wenjie Zhang, Yang Zhang, Zilin Zhao, Dejian Zhong, Xiaobin Zhuang
conference: No Venue
year: 2024
bibkey: anastassiou2024seed
additional_links: [{name: Code, url: 'https://bytedancespeech.github.io/seedtts_tech_report'},
  {name: Code, url: 'https://huggingface.co/discussions/paper/665fe7565a8aa91644bf74b8'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2406.02430'}]
tags: ["Has Code", "Model Architecture"]
short_authors: Anastassiou et al.
---
We introduce Seed-TTS, a family of large-scale autoregressive text-to-speech (TTS) models capable of generating speech that is virtually indistinguishable from human speech. Seed-TTS serves as a foundation model for speech generation and excels in speech in-context learning, achieving performance in speaker similarity and naturalness that matches ground truth human speech in both objective and subjective evaluations. With fine-tuning, we achieve even higher subjective scores across these metrics. Seed-TTS offers superior controllability over various speech attributes such as emotion and is capable of generating highly expressive and diverse speech for speakers in the wild. Furthermore, we propose a self-distillation method for speech factorization, as well as a reinforcement learning approach to enhance model robustness, speaker similarity, and controllability. We additionally present a non-autoregressive (NAR) variant of the Seed-TTS model, named Seed-TTS_DiT, which utilizes a fully diffusion-based architecture. Unlike previous NAR-based TTS systems, Seed-TTS_DiT does not depend on pre-estimated phoneme durations and performs speech generation through end-to-end processing. We demonstrate that this variant achieves comparable performance to the language model-based variant and showcase its effectiveness in speech editing. We encourage readers to listen to demos at https://bytedancespeech.github.io/seedtts_tech_report.

https://huggingface.co/discussions/paper/665fe7565a8aa91644bf74b8