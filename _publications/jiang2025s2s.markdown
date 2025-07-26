---
layout: publication
title: S2s-arena, Evaluating Speech2speech Protocols On Instruction Following With
  Paralinguistic Information
authors: Feng Jiang, Zhiyu Lin, Fan Bu, Yuhao Du, Benyou Wang, Haizhou Li
conference: No Venue
year: 2025
bibkey: jiang2025s2s
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2503.05085'}]
tags: ["Evaluation", "Instruction Following"]
short_authors: Jiang et al.
---
The rapid development of large language models (LLMs) has brought significant attention to speech models, particularly recent progress in speech2speech protocols supporting speech input and output. However, the existing benchmarks adopt automatic text-based evaluators for evaluating the instruction following ability of these models lack consideration for paralinguistic information in both speech understanding and generation. To address these issues, we introduce S2S-Arena, a novel arena-style S2S benchmark that evaluates instruction-following capabilities with paralinguistic information in both speech-in and speech-out across real-world tasks. We design 154 samples that fused TTS and live recordings in four domains with 21 tasks and manually evaluate existing popular speech models in an arena-style manner. The experimental results show that: (1) in addition to the superior performance of GPT-4o, the speech model of cascaded ASR, LLM, and TTS outperforms the jointly trained model after text-speech alignment in speech2speech protocols; (2) considering paralinguistic information, the knowledgeability of the speech model mainly depends on the LLM backbone, and the multilingual support of that is limited by the speech module; (3) excellent speech models can already understand the paralinguistic information in speech input, but generating appropriate audio with paralinguistic information is still a challenge.

https://huggingface.co/discussions/paper/67ced890a0db83a841e09c1b