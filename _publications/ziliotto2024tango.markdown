---
layout: publication
title: 'TANGO: Training-free Embodied AI Agents For Open-world Tasks'
authors: Ziliotto et al.
conference: Cybernetics and Systems
year: 2024
bibkey: ziliotto2024tango
citations: 72
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2412.10402'}]
tags: [Training Techniques, Prompting, Agentic, Reinforcement Learning, Fine Tuning]
---
Large Language Models (LLMs) have demonstrated excellent capabilities in
composing various modules together to create programs that can perform complex
reasoning tasks on images. In this paper, we propose TANGO, an approach that
extends the program composition via LLMs already observed for images, aiming to
integrate those capabilities into embodied agents capable of observing and
acting in the world. Specifically, by employing a simple PointGoal Navigation
model combined with a memory-based exploration policy as a foundational
primitive for guiding an agent through the world, we show how a single model
can address diverse tasks without additional training. We task an LLM with
composing the provided primitives to solve a specific task, using only a few
in-context examples in the prompt. We evaluate our approach on three key
Embodied AI tasks: Open-Set ObjectGoal Navigation, Multi-Modal Lifelong
Navigation, and Open Embodied Question Answering, achieving state-of-the-art
results without any specific fine-tuning in challenging zero-shot scenarios.