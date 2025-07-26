---
layout: publication
title: 'Chatanything: Facetime Chat With Llm-enhanced Personas'
authors: Yilin Zhao, Xinbin Yuan, Shanghua Gao, Zhijie Lin, Qibin Hou, Jiashi Feng,
  Daquan Zhou
conference: No Venue
year: 2023
bibkey: zhao2023chatanything
additional_links: [{name: Code, url: 'https://chatanything.github.io/'}, {name: Code,
    url: 'https://huggingface.co/discussions/paper/6552f3bc0166ff6bd22f4642'}, {name: Paper,
    url: 'https://arxiv.org/abs/hf2311.06772'}]
tags: ["Tools"]
short_authors: Zhao et al.
---
In this technical report, we target generating anthropomorphized personas for LLM-based characters in an online manner, including visual appearance, personality and tones, with only text descriptions. To achieve this, we first leverage the in-context learning capability of LLMs for personality generation by carefully designing a set of system prompts. We then propose two novel concepts: the mixture of voices (MoV) and the mixture of diffusers (MoD) for diverse voice and appearance generation. For MoV, we utilize the text-to-speech (TTS) algorithms with a variety of pre-defined tones and select the most matching one based on the user-provided text description automatically. For MoD, we combine the recent popular text-to-image generation techniques and talking head algorithms to streamline the process of generating talking objects. We termed the whole framework as ChatAnything. With it, users could be able to animate anything with any personas that are anthropomorphic using just a few text inputs. However, we have observed that the anthropomorphic objects produced by current generative models are often undetectable by pre-trained face landmark detectors, leading to failure of the face motion generation, even if these faces possess human-like appearances because those images are nearly seen during the training (e.g., OOD samples). To address this issue, we incorporate pixel-level guidance to infuse human face landmarks during the image generation phase. To benchmark these metrics, we have built an evaluation dataset. Based on it, we verify that the detection rate of the face landmark is significantly increased from 57.0% to 92.5% thus allowing automatic face animation based on generated speech content. The code and more results can be found at https://chatanything.github.io/.

https://huggingface.co/discussions/paper/6552f3bc0166ff6bd22f4642