---
layout: publication
title: The Vector Grounding Problem
authors: "Dimitri Coelho Mollo, Rapha\xEBl Milli\xE8re"
conference: Arxiv
year: 2023
citations: 19
bibkey: mollo2023vector
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2304.01481'}]
tags: [Training Techniques, Pre-Training, Fine-Tuning, Interpretability and Explainability,
  Reinforcement Learning, Multimodal Models]
---
The remarkable performance of large language models (LLMs) on complex linguistic tasks has sparked debate about their capabilities. Unlike humans, these models learn language solely from textual data without directly interacting with the world. Yet they generate seemingly meaningful text on diverse topics. This achievement has renewed interest in the classical `Symbol Grounding Problem' -- the question of whether the internal representations and outputs of symbolic AI systems can possess intrinsic meaning that is not parasitic on external interpretation. Although modern LLMs compute over vectors rather than symbols, an analogous problem arises for these systems, which we call the Vector Grounding Problem. This paper has two main goals. First, we distinguish five main notions of grounding that are often conflated in the literature, and argue that only one of them, which we call referential grounding, is relevant to the Vector Grounding Problem. Second, drawing on philosophical theories of representational content, we provide two arguments for the claim that LLMs and related systems can achieve referential grounding: (1) through preference fine-tuning methods that explicitly establish world-involving functions, and (2) through pre-training alone, which in limited domains may select for internal states with world-involving content, as mechanistic interpretability research suggests. Through these pathways, LLMs can establish connections to the world sufficient for intrinsic meaning. One potentially surprising implication of our discussion is that that multimodality and embodiment are neither necessary nor sufficient to overcome the Grounding Problem.