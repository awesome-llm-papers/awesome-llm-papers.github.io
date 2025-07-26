---
layout: publication
title: 'Sherlock: Self-correcting Reasoning In Vision-language Models'
authors: Yi Ding, Ruqi Zhang
conference: No Venue
year: 2025
bibkey: ding2025sherlock
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2505.22651'}]
tags: ["Tools"]
short_authors: Yi Ding, Ruqi Zhang
---
Reasoning Vision-Language Models (VLMs) have shown promising performance on complex multimodal tasks. However, they still face significant challenges: they are highly sensitive to reasoning errors, require large volumes of annotated data or accurate verifiers, and struggle to generalize beyond specific domains. To address these limitations, we explore self-correction as a strategy to enhance reasoning VLMs. We first conduct an in-depth analysis of reasoning VLMs' self-correction abilities and identify key gaps. Based on our findings, we introduce Sherlock, a self-correction and self-improvement training framework. Sherlock introduces a trajectory-level self-correction objective, a preference data construction method based on visual perturbation, and a dynamic beta for preference tuning. Once the model acquires self-correction capabilities using only 20k randomly sampled annotated data, it continues to self-improve without external supervision. Built on the Llama3.2-Vision-11B model, Sherlock achieves remarkable results across eight benchmarks, reaching an average accuracy of 64.1 with direct generation and 65.4 after self-correction. It outperforms LLaVA-CoT (63.2), Mulberry (63.9), and LlamaV-o1 (63.4) while using less than 20% of the annotated data.

https://huggingface.co/discussions/paper/6837ffdf1bfb4a669ad6de71