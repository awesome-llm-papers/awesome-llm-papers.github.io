---
layout: publication
title: 'Mocha: Towards Movie-grade Talking Character Synthesis'
authors: Cong Wei, Bo Sun, Haoyu Ma, Ji Hou, Felix Juefei-xu, Zecheng He, Xiaoliang
  Dai, Luxin Zhang, Kunpeng Li, Tingbo Hou, Animesh Sinha, Peter Vajda, Wenhu Chen
conference: No Venue
year: 2025
bibkey: wei2025mocha
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2503.23307'}]
tags: ["Model Architecture"]
short_authors: Wei et al.
---
Recent advancements in video generation have achieved impressive motion realism, yet they often overlook character-driven storytelling, a crucial task for automated film, animation generation. We introduce Talking Characters, a more realistic task to generate talking character animations directly from speech and text. Unlike talking head, Talking Characters aims at generating the full portrait of one or more characters beyond the facial region. In this paper, we propose MoCha, the first of its kind to generate talking characters. To ensure precise synchronization between video and speech, we propose a speech-video window attention mechanism that effectively aligns speech and video tokens. To address the scarcity of large-scale speech-labeled video datasets, we introduce a joint training strategy that leverages both speech-labeled and text-labeled video data, significantly improving generalization across diverse character actions. We also design structured prompt templates with character tags, enabling, for the first time, multi-character conversation with turn-based dialogue-allowing AI-generated characters to engage in context-aware conversations with cinematic coherence. Extensive qualitative and quantitative evaluations, including human preference studies and benchmark comparisons, demonstrate that MoCha sets a new standard for AI-generated cinematic storytelling, achieving superior realism, expressiveness, controllability and generalization.

https://huggingface.co/discussions/paper/67eb4bd3eca57c4eebbb34c7