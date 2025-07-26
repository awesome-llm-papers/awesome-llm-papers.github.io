---
layout: publication
title: 'Videopoet: A Large Language Model For Zero-shot Video Generation'
authors: "Dan Kondratyuk, Lijun Yu, Xiuye Gu, Jos\xE9 Lezama, Jonathan Huang, Rachel\
  \ Hornung, Hartwig Adam, Hassan Akbari, Yair Alon, Vighnesh Birodkar, Yong Cheng,\
  \ Ming-chang Chiu, Josh Dillon, Irfan Essa, Agrim Gupta, Meera Hahn, Anja Hauth,\
  \ David Hendon, Alonso Martinez, David Minnen, David Ross, Grant Schindler, Mikhail\
  \ Sirotenko, Kihyuk Sohn, Krishna Somandepalli, Huisheng Wang, Jimmy Yan, Ming-hsuan\
  \ Yang, Xuan Yang, Bryan Seybold, Lu Jiang"
conference: No Venue
year: 2023
bibkey: kondratyuk2023videopoet
additional_links: [{name: Code, url: 'http://sites.research.google/videopoet/'}, {
    name: Code, url: 'https://huggingface.co/discussions/paper/6584e935e07563d421f56a4e'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2312.14125'}]
tags: ["Model Architecture", "Tools"]
short_authors: Kondratyuk et al.
---
We present VideoPoet, a language model capable of synthesizing high-quality video, with matching audio, from a large variety of conditioning signals. VideoPoet employs a decoder-only transformer architecture that processes multimodal inputs -- including images, videos, text, and audio. The training protocol follows that of Large Language Models (LLMs), consisting of two stages: pretraining and task-specific adaptation. During pretraining, VideoPoet incorporates a mixture of multimodal generative objectives within an autoregressive Transformer framework. The pretrained LLM serves as a foundation that can be adapted for a range of video generation tasks. We present empirical results demonstrating the model's state-of-the-art capabilities in zero-shot video generation, specifically highlighting VideoPoet's ability to generate high-fidelity motions. Project page: http://sites.research.google/videopoet/

https://huggingface.co/discussions/paper/6584e935e07563d421f56a4e