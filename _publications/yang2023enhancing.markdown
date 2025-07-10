---
layout: publication
title: 'Zhongjing: Enhancing The Chinese Medical Capabilities Of Large Language Model
  Through Expert Feedback And Real-world Multi-turn Dialogue'
authors: Songhua Yang et al.
conference: Proceedings of the AAAI Conference on Artificial Intelligence
year: 2023
citations: 45
bibkey: yang2023enhancing
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2308.03549'}, {name: Code,
    url: 'https://github.com/SupritYoung/Zhongjing'}]
tags: [Responsible AI, Has Code, Model Architecture, GPT, Fine-Tuning, Applications,
  Reinforcement Learning, Pre-Training, Agentic, Training Techniques, Evaluation]
---
Recent advances in Large Language Models (LLMs) have achieved remarkable
breakthroughs in understanding and responding to user intents. However, their
performance lag behind general use cases in some expertise domains, such as
Chinese medicine. Existing efforts to incorporate Chinese medicine into LLMs
rely on Supervised Fine-Tuning (SFT) with single-turn and distilled dialogue
data. These models lack the ability for doctor-like proactive inquiry and
multi-turn comprehension and cannot align responses with experts' intentions.
In this work, we introduce Zhongjing, the first Chinese medical LLaMA-based LLM
that implements an entire training pipeline from continuous pre-training, SFT,
to Reinforcement Learning from Human Feedback (RLHF). Additionally, we
construct a Chinese multi-turn medical dialogue dataset of 70,000 authentic
doctor-patient dialogues, CMtMedQA, which significantly enhances the model's
capability for complex dialogue and proactive inquiry initiation. We also
define a refined annotation rule and evaluation criteria given the unique
characteristics of the biomedical domain. Extensive experimental results show
that Zhongjing outperforms baselines in various capacities and matches the
performance of ChatGPT in some abilities, despite the 100x parameters. Ablation
studies also demonstrate the contributions of each component: pre-training
enhances medical knowledge, and RLHF further improves instruction-following
ability and safety. Our code, datasets, and models are available at
https://github.com/SupritYoung/Zhongjing.