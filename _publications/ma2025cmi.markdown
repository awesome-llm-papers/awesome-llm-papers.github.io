---
layout: publication
title: 'Cmi-bench: A Comprehensive Benchmark For Evaluating Music Instruction Following'
authors: Yinghao Ma, Siyou Li, Juntao Yu, Emmanouil Benetos, Akira Maezawa
conference: No Venue
year: 2025
bibkey: ma2025cmi
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2506.12285'}]
tags: ["Evaluation", "Instruction Following"]
short_authors: Ma et al.
---
Recent advances in audio-text large language models (LLMs) have opened new possibilities for music understanding and generation. However, existing benchmarks are limited in scope, often relying on simplified tasks or multi-choice evaluations that fail to reflect the complexity of real-world music analysis. We reinterpret a broad range of traditional MIR annotations as instruction-following formats and introduce CMI-Bench, a comprehensive music instruction following benchmark designed to evaluate audio-text LLMs on a diverse set of music information retrieval (MIR) tasks. These include genre classification, emotion regression, emotion tagging, instrument classification, pitch estimation, key detection, lyrics transcription, melody extraction, vocal technique recognition, instrument performance technique detection, music tagging, music captioning, and (down)beat tracking: reflecting core challenges in MIR research. Unlike previous benchmarks, CMI-Bench adopts standardized evaluation metrics consistent with previous state-of-the-art MIR models, ensuring direct comparability with supervised approaches. We provide an evaluation toolkit supporting all open-source audio-textual LLMs, including LTU, Qwen-audio, SALMONN, MusiLingo, etc. Experiment results reveal significant performance gaps between LLMs and supervised models, along with their culture, chronological and gender bias, highlighting the potential and limitations of current models in addressing MIR tasks. CMI-Bench establishes a unified foundation for evaluating music instruction following, driving progress in music-aware LLMs.

https://huggingface.co/discussions/paper/6852b15a7eb90a35d35de608