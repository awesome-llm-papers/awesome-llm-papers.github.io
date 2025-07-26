---
layout: publication
title: 'Photomaker: Customizing Realistic Human Photos Via Stacked ID Embedding'
authors: Zhen Li, Mingdeng Cao, Xintao Wang, Zhongang Qi, Ming-ming Cheng, Ying Shan
conference: No Venue
year: 2023
bibkey: li2023photomaker
additional_links: [{name: Code, url: 'https://photo-maker.github.io/'}, {name: Code,
    url: 'https://huggingface.co/discussions/paper/65728d8ccca2247f3f2acff6'}, {name: Paper,
    url: 'https://arxiv.org/abs/hf2312.04461'}]
tags: ["Applications"]
short_authors: Li et al.
---
Recent advances in text-to-image generation have made remarkable progress in synthesizing realistic human photos conditioned on given text prompts. However, existing personalized generation methods cannot simultaneously satisfy the requirements of high efficiency, promising identity (ID) fidelity, and flexible text controllability. In this work, we introduce PhotoMaker, an efficient personalized text-to-image generation method, which mainly encodes an arbitrary number of input ID images into a stack ID embedding for preserving ID information. Such an embedding, serving as a unified ID representation, can not only encapsulate the characteristics of the same input ID comprehensively, but also accommodate the characteristics of different IDs for subsequent integration. This paves the way for more intriguing and practically valuable applications. Besides, to drive the training of our PhotoMaker, we propose an ID-oriented data construction pipeline to assemble the training data. Under the nourishment of the dataset constructed through the proposed pipeline, our PhotoMaker demonstrates better ID preservation ability than test-time fine-tuning based methods, yet provides significant speed improvements, high-quality generation results, strong generalization capabilities, and a wide range of applications. Our project page is available at https://photo-maker.github.io/

https://huggingface.co/discussions/paper/65728d8ccca2247f3f2acff6