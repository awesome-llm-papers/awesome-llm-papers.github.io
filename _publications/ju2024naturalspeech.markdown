---
layout: publication
title: 'Naturalspeech 3: Zero-shot Speech Synthesis With Factorized Codec And Diffusion
  Models'
authors: Zeqian Ju, Yuancheng Wang, Kai Shen, Xu Tan, Detai Xin, Dongchao Yang, Yanqing
  Liu, Yichong Leng, Kaitao Song, Siliang Tang, Zhizheng Wu, Tao Qin, Xiang-yang Li,
  Wei Ye, Shikun Zhang, Jiang Bian, Lei He, Jinyu Li, Sheng Zhao
conference: No Venue
year: 2024
bibkey: ju2024naturalspeech
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/65e7f92674ab027493c2f444'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2403.03100'}]
tags: ["Efficiency", "Training Techniques"]
short_authors: Ju et al.
---
While recent large-scale text-to-speech (TTS) models have achieved significant progress, they still fall short in speech quality, similarity, and prosody. Considering speech intricately encompasses various attributes (e.g., content, prosody, timbre, and acoustic details) that pose significant challenges for generation, a natural idea is to factorize speech into individual subspaces representing different attributes and generate them individually. Motivated by it, we propose NaturalSpeech 3, a TTS system with novel factorized diffusion models to generate natural speech in a zero-shot way. Specifically, 1) we design a neural codec with factorized vector quantization (FVQ) to disentangle speech waveform into subspaces of content, prosody, timbre, and acoustic details; 2) we propose a factorized diffusion model to generate attributes in each subspace following its corresponding prompt. With this factorization design, NaturalSpeech 3 can effectively and efficiently model the intricate speech with disentangled subspaces in a divide-and-conquer way. Experiments show that NaturalSpeech 3 outperforms the state-of-the-art TTS systems on quality, similarity, prosody, and intelligibility. Furthermore, we achieve better performance by scaling to 1B parameters and 200K hours of training data.

https://huggingface.co/discussions/paper/65e7f92674ab027493c2f444