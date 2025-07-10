---
layout: publication
title: 'GPT-4 Enhanced Multimodal Grounding For Autonomous Driving: Leveraging Cross-modal
  Attention With Large Language Models'
authors: Haicheng Liao et al.
conference: Communications in Transportation Research
year: 2023
citations: 35
bibkey: liao2023gpt
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2312.03543'}]
tags: [Security, Model Architecture, Attention Mechanism, GPT, Transformer, RAG, Applications,
  Tools, Reinforcement Learning, Multimodal Models, Efficiency and Optimization, Training
    Techniques, Evaluation]
---
In the field of autonomous vehicles (AVs), accurately discerning commander
intent and executing linguistic commands within a visual context presents a
significant challenge. This paper introduces a sophisticated encoder-decoder
framework, developed to address visual grounding in AVs.Our Context-Aware
Visual Grounding (CAVG) model is an advanced system that integrates five core
encoders-Text, Image, Context, and Cross-Modal-with a Multimodal decoder. This
integration enables the CAVG model to adeptly capture contextual semantics and
to learn human emotional features, augmented by state-of-the-art Large Language
Models (LLMs) including GPT-4. The architecture of CAVG is reinforced by the
implementation of multi-head cross-modal attention mechanisms and a
Region-Specific Dynamic (RSD) layer for attention modulation. This
architectural design enables the model to efficiently process and interpret a
range of cross-modal inputs, yielding a comprehensive understanding of the
correlation between verbal commands and corresponding visual scenes. Empirical
evaluations on the Talk2Car dataset, a real-world benchmark, demonstrate that
CAVG establishes new standards in prediction accuracy and operational
efficiency. Notably, the model exhibits exceptional performance even with
limited training data, ranging from 50% to 75% of the full dataset. This
feature highlights its effectiveness and potential for deployment in practical
AV applications. Moreover, CAVG has shown remarkable robustness and
adaptability in challenging scenarios, including long-text command
interpretation, low-light conditions, ambiguous command contexts, inclement
weather conditions, and densely populated urban environments. The code for the
proposed model is available at our Github.