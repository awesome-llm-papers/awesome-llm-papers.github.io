---
layout: publication
title: 'An Open Recipe: Adapting Language-specific Llms To A Reasoning Model In One
  Day Via Model Merging'
authors: Kunat Pipatanakul, Pittawat Taveekitworachai, Potsawee Manakul, Kasima Tharnpipitchai
conference: No Venue
year: 2025
bibkey: pipatanakul2025open
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/67aea8d8926b659c7e959bee'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2502.09056'}]
tags: ["Datasets", "Training Techniques"]
short_authors: Pipatanakul et al.
---
This paper investigates data selection and model merging methodologies aimed at incorporating advanced reasoning capabilities such as those of DeepSeek R1 into language-specific large language models (LLMs), with a particular focus on the Thai LLM. Our goal is to enhance the reasoning capabilities of language-specific LLMs while maintaining their target language abilities. DeepSeek R1 excels in reasoning but primarily benefits high-resource languages such as English and Chinese. However, low-resource languages remain underserved due to the dominance of English-centric training data and model optimizations, which limit performance in these languages. This limitation results in unreliable code-switching and diminished effectiveness on tasks in low-resource languages. Meanwhile, local and regional LLM initiatives have attempted to bridge this gap by developing language-specific LLMs that focus on improving local linguistic fidelity. We demonstrate that, with only publicly available datasets and a computational budget of $120, it is possible to enhance the reasoning capabilities of language-specific LLMs to match the level of DeepSeek R1, without compromising their performance on target language tasks.

https://huggingface.co/discussions/paper/67aea8d8926b659c7e959bee