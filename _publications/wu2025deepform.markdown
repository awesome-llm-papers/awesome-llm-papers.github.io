---
layout: publication
title: 'Deepform: Reasoning Large Language Model For Communication System Formulation'
authors: Wu et al.
conference: JAMA Network Open
year: 2025
bibkey: wu2025deepform
citations: 163
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2506.08551'}]
tags: [Training Techniques, Agentic, Tools, Reinforcement Learning, Fine Tuning, Datasets]
---
Communication system formulation is critical for advancing 6G and future wireless technologies, yet it remains a complex, expertise-intensive task. While Large Language Models (LLMs) offer potential, existing general-purpose models often lack the specialized domain knowledge, nuanced reasoning capabilities, and access to high-quality, domain-specific training data required for adapting a general LLM into an LLM specially for communication system formulation. To bridge this gap, we introduce DeepForm, the first reasoning LLM specially for automated communication system formulation. We propose the world-first large-scale, open-source dataset meticulously curated for this domain called Communication System Formulation Reasoning Corpus (CSFRC). Our framework employs a two-stage training strategy: first, Supervised Fine-Tuning (SFT) with Chain-of-Thought (CoT) data to distill domain knowledge; second, a novel rule-based Reinforcement Learning (RL) algorithm, C-ReMax based on ReMax, to cultivate advanced modeling capabilities and elicit sophisticated reasoning patterns like self-correction and verification. Extensive experiments demonstrate that our model achieves state-of-the-art performance, significantly outperforming larger proprietary LLMs on diverse senerios. We will release related resources to foster further research in this area after the paper is accepted.