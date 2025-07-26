---
layout: publication
title: 'Llmvox: Autoregressive Streaming Text-to-speech Model For Any LLM'
authors: Sambal Shikhar, Mohammed Irfan Kurpath, Sahal Shaji Mullappilly, Jean Lahoud,
  Fahad Khan, Rao Muhammad Anwer, Salman Khan, Hisham Cholakkal
conference: No Venue
year: 2025
bibkey: shikhar2025llmvox
additional_links: [{name: Code, url: 'https://mbzuai-oryx.github.io/LLMVoX'}, {name: Code,
    url: 'https://huggingface.co/discussions/paper/67cacfd95dc0bf8f5e6fc84e'}, {name: Paper,
    url: 'https://arxiv.org/abs/hf2503.04724'}]
tags: ["Has Code"]
short_authors: Shikhar et al.
---
Recent advancements in speech-to-speech dialogue systems leverage LLMs for multimodal interactions, yet they remain hindered by fine-tuning requirements, high computational overhead, and text-speech misalignment. Existing speech-enabled LLMs often degrade conversational quality by modifying the LLM, thereby compromising its linguistic capabilities. In contrast, we propose LLMVoX, a lightweight 30M-parameter, LLM-agnostic, autoregressive streaming TTS system that generates high-quality speech with low latency, while fully preserving the capabilities of the base LLM. Our approach achieves a significantly lower Word Error Rate compared to speech-enabled LLMs, while operating at comparable latency and UTMOS score. By decoupling speech synthesis from LLM processing via a multi-queue token streaming system, LLMVoX supports seamless, infinite-length dialogues. Its plug-and-play design also facilitates extension to various tasks with different backbones. Furthermore, LLMVoX generalizes to new languages with only dataset adaptation, attaining a low Character Error Rate on an Arabic speech task. Additionally, we have integrated LLMVoX with a Vision-Language Model to create an omni-model with speech, text, and vision capabilities, without requiring additional multimodal training. Our code base and project page is available at https://mbzuai-oryx.github.io/LLMVoX .

https://huggingface.co/discussions/paper/67cacfd95dc0bf8f5e6fc84e