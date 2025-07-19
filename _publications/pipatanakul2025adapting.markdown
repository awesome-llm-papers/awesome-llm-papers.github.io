---
layout: publication
title: Adapting Language-specific Llms To A Reasoning Model In One Day Via Model Merging
  -- An Open Recipe
authors: Pipatanakul et al.
conference: 2024 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2025
bibkey: pipatanakul2025adapting
citations: 75
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2502.09056'}]
tags: [Training Techniques, CVPR, Efficiency And Optimization, Datasets, Merging]
---
This paper investigates data selection and model merging methodologies aimed
at incorporating advanced reasoning capabilities such as those of DeepSeek R1
into language-specific large language models (LLMs), with a particular focus on
the Thai LLM. Our goal is to enhance the reasoning capabilities of
language-specific LLMs while maintaining their target language abilities.
DeepSeek R1 excels in reasoning but primarily benefits high-resource languages
such as English and Chinese. However, low-resource languages remain underserved
due to the dominance of English-centric training data and model optimizations,
which limit performance in these languages. This limitation results in
unreliable code-switching and diminished effectiveness on tasks in low-resource
languages. Meanwhile, local and regional LLM initiatives have attempted to
bridge this gap by developing language-specific LLMs that focus on improving
local linguistic fidelity. We demonstrate that, with only publicly available
datasets and a computational budget of $120, it is possible to enhance the
reasoning capabilities of language-specific LLMs to match the level of DeepSeek
R1, without compromising their performance on target language tasks.