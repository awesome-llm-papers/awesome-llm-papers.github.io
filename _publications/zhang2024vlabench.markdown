---
layout: publication
title: 'Vlabench: A Large-scale Benchmark For Language-conditioned Robotics Manipulation
  With Long-horizon Reasoning Tasks'
authors: Zhang et al.
conference: IEEE Robotics and Automation Letters
year: 2024
bibkey: zhang2024vlabench
citations: 58
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2412.18194'}]
tags: [Training Techniques, Agentic, Tools, Evaluation, Reinforcement Learning, Multimodal
    Models, Datasets]
---
General-purposed embodied agents are designed to understand the users'
natural instructions or intentions and act precisely to complete universal
tasks. Recently, methods based on foundation models especially
Vision-Language-Action models (VLAs) have shown a substantial potential to
solve language-conditioned manipulation (LCM) tasks well. However, existing
benchmarks do not adequately meet the needs of VLAs and relative algorithms. To
better define such general-purpose tasks in the context of LLMs and advance the
research in VLAs, we present VLABench, an open-source benchmark for evaluating
universal LCM task learning. VLABench provides 100 carefully designed
categories of tasks, with strong randomization in each category of task and a
total of 2000+ objects. VLABench stands out from previous benchmarks in four
key aspects: 1) tasks requiring world knowledge and common sense transfer, 2)
natural language instructions with implicit human intentions rather than
templates, 3) long-horizon tasks demanding multi-step reasoning, and 4)
evaluation of both action policies and language model capabilities. The
benchmark assesses multiple competencies including understanding of
mesh\&texture, spatial relationship, semantic instruction, physical laws,
knowledge transfer and reasoning, etc. To support the downstream finetuning, we
provide high-quality training data collected via an automated framework
incorporating heuristic skills and prior information. The experimental results
indicate that both the current state-of-the-art pretrained VLAs and the
workflow based on VLMs face challenges in our tasks.