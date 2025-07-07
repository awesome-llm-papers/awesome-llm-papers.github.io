---
layout: publication
title: 'Llm-grounder: Open-vocabulary 3D Visual Grounding With Large Language Model
  As An Agent'
authors: Jianing Yang et al.
conference: Arxiv
year: 2023
citations: 16
bibkey: yang2023llm
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2309.12311'}]
tags: [Training Techniques, Agentic, Multimodal Models]
---
3D visual grounding is a critical skill for household robots, enabling them
to navigate, manipulate objects, and answer questions based on their
environment. While existing approaches often rely on extensive labeled data or
exhibit limitations in handling complex language queries, we propose
LLM-Grounder, a novel zero-shot, open-vocabulary, Large Language Model
(LLM)-based 3D visual grounding pipeline. LLM-Grounder utilizes an LLM to
decompose complex natural language queries into semantic constituents and
employs a visual grounding tool, such as OpenScene or LERF, to identify objects
in a 3D scene. The LLM then evaluates the spatial and commonsense relations
among the proposed objects to make a final grounding decision. Our method does
not require any labeled training data and can generalize to novel 3D scenes and
arbitrary text queries. We evaluate LLM-Grounder on the ScanRefer benchmark and
demonstrate state-of-the-art zero-shot grounding accuracy. Our findings
indicate that LLMs significantly improve the grounding capability, especially
for complex language queries, making LLM-Grounder an effective approach for 3D
vision-language tasks in robotics. Videos and interactive demos can be found on
the project website https://chat-with-nerf.github.io/ .