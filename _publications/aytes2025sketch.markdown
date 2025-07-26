---
layout: publication
title: 'Sketch-of-thought: Efficient LLM Reasoning With Adaptive Cognitive-inspired
  Sketching'
authors: Simon A. Aytes, Jinheon Baek, Sung Ju Hwang
conference: No Venue
year: 2025
bibkey: aytes2025sketch
additional_links: [{name: Code, url: 'https://www.github.com/SimonAytes/SoT'}, {name: Code,
    url: 'https://huggingface.co/discussions/paper/67ce4c035847e4787a7ebf4c'}, {name: Paper,
    url: 'https://arxiv.org/abs/hf2503.05179'}]
tags: ["Datasets", "Evaluation", "Has Code", "Prompting", "Tools"]
short_authors: Simon A. Aytes, Jinheon Baek, Sung Ju Hwang
---
Recent advances in large language models have demonstrated remarkable reasoning capabilities through Chain of Thought (CoT) prompting, but often at the cost of excessive verbosity in their intermediate outputs, which increases computational overhead. We introduce Sketch-of-Thought (SoT), a novel prompting framework that combines cognitive-inspired reasoning paradigms with linguistic constraints to minimize token usage while preserving reasoning accuracy. SoT is designed as a flexible framework that can incorporate any custom reasoning paradigms based on cognitive science, and we instantiate it with three such paradigms - Conceptual Chaining, Chunked Symbolism, and Expert Lexicons - each tailored to different reasoning tasks and selected dynamically via a lightweight routing model. Through comprehensive evaluation across 15 reasoning datasets with multiple languages and multimodal scenarios, we demonstrate that SoT achieves token reductions of 76% with negligible accuracy impact. In certain domains like mathematical and multi-hop reasoning, it even improves accuracy while using significantly fewer tokens. Our code is publicly available: https://www.github.com/SimonAytes/SoT.

https://huggingface.co/discussions/paper/67ce4c035847e4787a7ebf4c