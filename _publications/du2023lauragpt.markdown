---
layout: publication
title: 'Lauragpt: Listen, Attend, Understand, And Regenerate Audio With GPT'
authors: Du et al.
conference: Proceedings of the 28th ACM International Conference on Multimedia
year: 2023
bibkey: du2023lauragpt
citations: 79
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2310.04673'}]
tags: [RAG, GPT, Transformer, Model Architecture, Multimodal Models]
---
Generative Pre-trained Transformer (GPT) models have achieved remarkable
performance on various natural language processing tasks, and have shown great
potential as backbones for audio-and-text large language models (LLMs).
Previous mainstream audio-and-text LLMs use discrete audio tokens to represent
both input and output audio; however, they suffer from performance degradation
on tasks such as automatic speech recognition, speech-to-text translation, and
speech enhancement over models using continuous speech features. In this paper,
we propose LauraGPT, a novel unified audio-and-text GPT-based LLM for audio
recognition, understanding, and generation. LauraGPT is a versatile LLM that
can process both audio and text inputs and generate outputs in either
modalities. We propose a novel data representation that combines continuous and
discrete features for audio: LauraGPT encodes input audio into continuous
representations using an audio encoder and generates output audio from discrete
codec codes. We propose a one-step codec vocoder to overcome the prediction
challenge caused by the multimodal distribution of codec tokens. We fine-tune
LauraGPT using supervised multi-task learning. Extensive experiments show that
LauraGPT consistently achieves comparable to superior performance compared to
strong baselines on a wide range of audio tasks related to content, semantics,
paralinguistics, and audio-signal analysis, such as automatic speech
recognition, speech-to-text translation, text-to-speech synthesis, speech
enhancement, automated audio captioning, speech emotion recognition, and spoken
language understanding.