---
layout: publication
title: Evolutionary Optimization Of Model Merging Recipes
authors: Takuya Akiba, Makoto Shing, Yujin Tang, Qi Sun, David Ha
conference: No Venue
year: 2024
bibkey: akiba2024evolutionary
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2403.13187'}]
tags: ["Efficiency", "Training Techniques"]
short_authors: Akiba et al.
---
We present a novel application of evolutionary algorithms to automate the creation of powerful foundation models. While model merging has emerged as a promising approach for LLM development due to its cost-effectiveness, it currently relies on human intuition and domain knowledge, limiting its potential. Here, we propose an evolutionary approach that overcomes this limitation by automatically discovering effective combinations of diverse open-source models, harnessing their collective intelligence without requiring extensive additional training data or compute. Our approach operates in both parameter space and data flow space, allowing for optimization beyond just the weights of the individual models. This approach even facilitates cross-domain merging, generating models like a Japanese LLM with Math reasoning capabilities. Surprisingly, our Japanese Math LLM achieved state-of-the-art performance on a variety of established Japanese LLM benchmarks, even surpassing models with significantly more parameters, despite not being explicitly trained for such tasks. Furthermore, a culturally-aware Japanese VLM generated through our approach demonstrates its effectiveness in describing Japanese culture-specific content, outperforming previous Japanese VLMs. This work not only contributes new state-of-the-art models back to the open-source community, but also introduces a new paradigm for automated model composition, paving the way for exploring alternative, efficient approaches to foundation model development.

https://huggingface.co/discussions/paper/65fb7f72ec1f99ad1f01f50d