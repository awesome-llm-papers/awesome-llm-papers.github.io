---
layout: publication
title: 'Chat-univi: Unified Visual Representation Empowers Large Language Models With
  Image And Video Understanding'
authors: Peng Jin, Ryuichi Takanobu, Wancai Zhang, Xiaochun Cao, Li Yuan
conference: Arxiv
year: 2023
citations: 21
bibkey: jin2023chat
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2311.08046'}, {name: Code,
    url: 'https://github.com/PKU-YuanGroup/Chat-UniVi'}]
tags: [RAG, Tools, Reinforcement Learning, Has Code, Multimodal Models]
---
Large language models have demonstrated impressive universal capabilities
across a wide range of open-ended tasks and have extended their utility to
encompass multimodal conversations. However, existing methods encounter
challenges in effectively handling both image and video understanding,
particularly with limited visual tokens. In this work, we introduce Chat-UniVi,
a Unified Vision-language model capable of comprehending and engaging in
conversations involving images and videos through a unified visual
representation. Specifically, we employ a set of dynamic visual tokens to
uniformly represent images and videos. This representation framework empowers
the model to efficiently utilize a limited number of visual tokens to
simultaneously capture the spatial details necessary for images and the
comprehensive temporal relationship required for videos. Moreover, we leverage
a multi-scale representation, enabling the model to perceive both high-level
semantic concepts and low-level visual details. Notably, Chat-UniVi is trained
on a mixed dataset containing both images and videos, allowing direct
application to tasks involving both mediums without requiring any
modifications. Extensive experimental results demonstrate that Chat-UniVi
consistently outperforms even existing methods exclusively designed for either
images or videos. Code is available at
https://github.com/PKU-YuanGroup/Chat-UniVi.