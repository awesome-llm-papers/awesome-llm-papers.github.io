---
layout: publication
title: 'Minimax-speech: Intrinsic Zero-shot Text-to-speech With A Learnable Speaker
  Encoder'
authors: Bowen Zhang, Congchao Guo, Geng Yang, Hang Yu, Haozhe Zhang, Heidi Lei, Jialong
  Mai, Junjie Yan, Kaiyue Yang, Mingqi Yang, Peikai Huang, Ruiyang Jin, Sitan Jiang,
  Weihua Cheng, Yawei Li, Yichen Xiao, Yiying Zhou, Yongmao Zhang, Yuan Lu, Yucen
  He
conference: No Venue
year: 2025
bibkey: zhang2025minimax
additional_links: [{name: Code, url: 'https://minimax-ai.github.io/tts_tech_report'},
  {name: Code, url: 'https://huggingface.co/discussions/paper/68244ea4bfb1b25f60400f4c'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2505.07916'}]
tags: ["Applications", "Has Code", "Model Architecture"]
short_authors: Zhang et al.
---
We introduce MiniMax-Speech, an autoregressive Transformer-based Text-to-Speech (TTS) model that generates high-quality speech. A key innovation is our learnable speaker encoder, which extracts timbre features from a reference audio without requiring its transcription. This enables MiniMax-Speech to produce highly expressive speech with timbre consistent with the reference in a zero-shot manner, while also supporting one-shot voice cloning with exceptionally high similarity to the reference voice. In addition, the overall quality of the synthesized audio is enhanced through the proposed Flow-VAE. Our model supports 32 languages and demonstrates excellent performance across multiple objective and subjective evaluations metrics. Notably, it achieves state-of-the-art (SOTA) results on objective voice cloning metrics (Word Error Rate and Speaker Similarity) and has secured the top position on the public TTS Arena leaderboard. Another key strength of MiniMax-Speech, granted by the robust and disentangled representations from the speaker encoder, is its extensibility without modifying the base model, enabling various applications such as: arbitrary voice emotion control via LoRA; text to voice (T2V) by synthesizing timbre features directly from text description; and professional voice cloning (PVC) by fine-tuning timbre features with additional data. We encourage readers to visit https://minimax-ai.github.io/tts_tech_report for more examples.

https://huggingface.co/discussions/paper/68244ea4bfb1b25f60400f4c