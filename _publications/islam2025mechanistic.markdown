---
layout: publication
title: Mechanistic Understandings Of Representation Vulnerabilities And Engineering
  Robust Vision Transformers
authors: Islam et al.
conference: Proceedings of the AAAI Conference on Artificial Intelligence
year: 2025
bibkey: islam2025mechanistic
citations: 118
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2502.04679'}]
tags: [Training Techniques, Transformer, Model Architecture, Reinforcement Learning,
  Security, Applications, Fine Tuning, AAAI]
---
While transformer-based models dominate NLP and vision applications, their
underlying mechanisms to map the input space to the label space semantically
are not well understood. In this paper, we study the sources of known
representation vulnerabilities of vision transformers (ViT), where perceptually
identical images can have very different representations and semantically
unrelated images can have the same representation. Our analysis indicates that
imperceptible changes to the input can result in significant representation
changes, particularly in later layers, suggesting potential instabilities in
the performance of ViTs. Our comprehensive study reveals that adversarial
effects, while subtle in early layers, propagate and amplify through the
network, becoming most pronounced in middle to late layers. This insight
motivates the development of NeuroShield-ViT, a novel defense mechanism that
strategically neutralizes vulnerable neurons in earlier layers to prevent the
cascade of adversarial effects. We demonstrate NeuroShield-ViT's effectiveness
across various attacks, particularly excelling against strong iterative
attacks, and showcase its remarkable zero-shot generalization capabilities.
Without fine-tuning, our method achieves a competitive accuracy of 77.8% on
adversarial examples, surpassing conventional robustness methods. Our results
shed new light on how adversarial effects propagate through ViT layers, while
providing a promising approach to enhance the robustness of vision transformers
against adversarial attacks. Additionally, they provide a promising approach to
enhance the robustness of vision transformers against adversarial attacks.