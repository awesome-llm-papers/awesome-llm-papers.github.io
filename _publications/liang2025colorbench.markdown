---
layout: publication
title: 'Colorbench: Can Vlms See And Understand The Colorful World? A Comprehensive
  Benchmark For Color Perception, Reasoning, And Robustness'
authors: Yijun Liang, Ming Li, Chenrui Fan, Ziyue Li, Dang Nguyen, Kwesi Cobbina,
  Shweta Bhardwaj, Jiuhai Chen, Fuxiao Liu, Tianyi Zhou
conference: No Venue
year: 2025
bibkey: liang2025colorbench
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/67ffedbeb0c26d6ec0b60a5b'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2504.10514'}]
tags: ["Applications", "Evaluation", "Prompting", "Security"]
short_authors: Liang et al.
---
Color plays an important role in human perception and usually provides critical clues in visual reasoning. However, it is unclear whether and how vision-language models (VLMs) can perceive, understand, and leverage color as humans. This paper introduces ColorBench, an innovative benchmark meticulously crafted to assess the capabilities of VLMs in color understanding, including color perception, reasoning, and robustness. By curating a suite of diverse test scenarios, with grounding in real applications, ColorBench evaluates how these models perceive colors, infer meanings from color-based cues, and maintain consistent performance under varying color transformations. Through an extensive evaluation of 32 VLMs with varying language models and vision encoders, our paper reveals some undiscovered findings: (i) The scaling law (larger models are better) still holds on ColorBench, while the language model plays a more important role than the vision encoder. (ii) However, the performance gaps across models are relatively small, indicating that color understanding has been largely neglected by existing VLMs. (iii) CoT reasoning improves color understanding accuracies and robustness, though they are vision-centric tasks. (iv) Color clues are indeed leveraged by VLMs on ColorBench but they can also mislead models in some tasks. These findings highlight the critical limitations of current VLMs and underscore the need to enhance color comprehension. Our ColorBenchcan serve as a foundational tool for advancing the study of human-level color understanding of multimodal AI.

https://huggingface.co/discussions/paper/67ffedbeb0c26d6ec0b60a5b