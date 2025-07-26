---
layout: publication
title: 'Hierspeech++: Bridging The Gap Between Semantic And Acoustic Representation
  Of Speech By Hierarchical Variational Inference For Zero-shot Speech Synthesis'
authors: Sang-hoon Lee, Ha-yeong Choi, Seung-bin Kim, Seong-whan Lee
conference: No Venue
year: 2023
bibkey: lee2023hierspeech
additional_links: [{name: Code, url: 'https://github.com/sh-lee-prml/HierSpeechpp'},
  {name: Code, url: 'https://huggingface.co/discussions/paper/655d90cabf82497038e70829'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2311.12454'}]
tags: ["Has Code", "Tools"]
short_authors: Lee et al.
---
Large language models (LLM)-based speech synthesis has been widely adopted in zero-shot speech synthesis. However, they require a large-scale data and possess the same limitations as previous autoregressive speech models, including slow inference speed and lack of robustness. This paper proposes HierSpeech++, a fast and strong zero-shot speech synthesizer for text-to-speech (TTS) and voice conversion (VC). We verified that hierarchical speech synthesis frameworks could significantly improve the robustness and expressiveness of the synthetic speech. Furthermore, we significantly improve the naturalness and speaker similarity of synthetic speech even in zero-shot speech synthesis scenarios. For text-to-speech, we adopt the text-to-vec framework, which generates a self-supervised speech representation and an F0 representation based on text representations and prosody prompts. Then, HierSpeech++ generates speech from the generated vector, F0, and voice prompt. We further introduce a high-efficient speech super-resolution framework from 16 kHz to 48 kHz. The experimental results demonstrated that the hierarchical variational autoencoder could be a strong zero-shot speech synthesizer given that it outperforms LLM-based and diffusion-based models. Moreover, we achieved the first human-level quality zero-shot speech synthesis. Audio samples and source code are available at https://github.com/sh-lee-prml/HierSpeechpp.

https://huggingface.co/discussions/paper/655d90cabf82497038e70829