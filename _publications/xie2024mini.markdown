---
layout: publication
title: 'Mini-omni: Language Models Can Hear, Talk While Thinking In Streaming'
authors: Zhifei Xie, Changqiao Wu
conference: No Venue
year: 2024
bibkey: xie2024mini
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2408.16725'}]
tags: ["Datasets", "Model Architecture", "Training Techniques"]
short_authors: Zhifei Xie, Changqiao Wu
---
Recent advances in language models have achieved significant progress. GPT-4o, as a new milestone, has enabled real-time conversations with humans, demonstrating near-human natural fluency. Such human-computer interaction necessitates models with the capability to perform reasoning directly with the audio modality and generate output in streaming. However, this remains beyond the reach of current academic models, as they typically depend on extra TTS systems for speech synthesis, resulting in undesirable latency. This paper introduces the Mini-Omni, an audio-based end-to-end conversational model, capable of real-time speech interaction. To achieve this capability, we propose a text-instructed speech generation method, along with batch-parallel strategies during inference to further boost the performance. Our method also helps to retain the original model's language capabilities with minimal degradation, enabling other works to establish real-time interaction capabilities. We call this training method "Any Model Can Talk". We also introduce the VoiceAssistant-400K dataset to fine-tune models optimized for speech output. To our best knowledge, Mini-Omni is the first fully end-to-end, open-source model for real-time speech interaction, offering valuable potential for future research.

https://huggingface.co/discussions/paper/66d138638a438492b07c2ebc