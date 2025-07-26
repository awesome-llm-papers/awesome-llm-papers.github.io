---
layout: publication
title: 'Wavtokenizer: An Efficient Acoustic Discrete Codec Tokenizer For Audio Language
  Modeling'
authors: Shengpeng Ji, Ziyue Jiang, Xize Cheng, Yifu Chen, Minghui Fang, Jialong Zuo,
  Qian Yang, Ruiqi Li, Ziang Zhang, Xiaoda Yang, Rongjie Huang, Yidi Jiang, Qian Chen,
  Siqi Zheng, Wen Wang, Zhou Zhao
conference: No Venue
year: 2024
bibkey: ji2024wavtokenizer
additional_links: [{name: Code, url: 'https://github.com/jishengpeng/WavTokenizer'},
  {name: Code, url: 'https://huggingface.co/discussions/paper/66d127fe3b8f08e1b2df384f'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2408.16532'}]
tags: ["Has Code"]
short_authors: Ji et al.
---
Language models have been effectively applied to modeling natural signals, such as images, video, speech, and audio. A crucial component of these models is the codec tokenizer, which compresses high-dimensional natural signals into lower-dimensional discrete tokens. In this paper, we introduce WavTokenizer, which offers several advantages over previous SOTA acoustic codec models in the audio domain: 1)extreme compression. By compressing the layers of quantizers and the temporal dimension of the discrete codec, one-second audio of 24kHz sampling rate requires only a single quantizer with 40 or 75 tokens. 2)improved subjective quality. Despite the reduced number of tokens, WavTokenizer achieves state-of-the-art reconstruction quality with outstanding UTMOS scores and inherently contains richer semantic information. Specifically, we achieve these results by designing a broader VQ space, extended contextual windows, and improved attention networks, as well as introducing a powerful multi-scale discriminator and an inverse Fourier transform structure. We conducted extensive reconstruction experiments in the domains of speech, audio, and music. WavTokenizer exhibited strong performance across various objective and subjective metrics compared to state-of-the-art models. We also tested semantic information, VQ utilization, and adaptability to generative models. Comprehensive ablation studies confirm the necessity of each module in WavTokenizer. The related code, demos, and pre-trained models are available at https://github.com/jishengpeng/WavTokenizer.

https://huggingface.co/discussions/paper/66d127fe3b8f08e1b2df384f