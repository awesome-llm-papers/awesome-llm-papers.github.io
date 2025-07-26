---
layout: publication
title: 'Theoremexplainagent: Towards Multimodal Explanations For LLM Theorem Understanding'
authors: Max Ku, Thomas Chong, Jonathan Leung, Krish Shah, Alvin Yu, Wenhu Chen
conference: No Venue
year: 2025
bibkey: ku2025theoremexplainagent
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2502.19400'}]
tags: ["Agentic"]
short_authors: Ku et al.
---
Understanding domain-specific theorems often requires more than just text-based reasoning; effective communication through structured visual explanations is crucial for deeper comprehension. While large language models (LLMs) demonstrate strong performance in text-based theorem reasoning, their ability to generate coherent and pedagogically meaningful visual explanations remains an open challenge. In this work, we introduce TheoremExplainAgent, an agentic approach for generating long-form theorem explanation videos (over 5 minutes) using Manim animations. To systematically evaluate multimodal theorem explanations, we propose TheoremExplainBench, a benchmark covering 240 theorems across multiple STEM disciplines, along with 5 automated evaluation metrics. Our results reveal that agentic planning is essential for generating detailed long-form videos, and the o3-mini agent achieves a success rate of 93.8% and an overall score of 0.77. However, our quantitative and qualitative studies show that most of the videos produced exhibit minor issues with visual element layout. Furthermore, multimodal explanations expose deeper reasoning flaws that text-based explanations fail to reveal, highlighting the importance of multimodal explanations.

https://huggingface.co/discussions/paper/67bfd6f25db054ee3c5a7699