---
layout: publication
title: 'Critique Fine-tuning: Learning To Critique Is More Effective Than Learning
  To Imitate'
authors: Yubo Wang, Xiang Yue, Wenhu Chen
conference: No Venue
year: 2025
bibkey: wang2025critique
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2501.17703'}]
tags: ["Fine-Tuning"]
short_authors: Yubo Wang, Xiang Yue, Wenhu Chen
---
Supervised Fine-Tuning (SFT) is commonly used to train language models to imitate annotated responses for given instructions. In this paper, we challenge this paradigm and propose Critique Fine-Tuning (CFT), a strategy where models learn to critique noisy responses rather than simply imitate correct ones. Inspired by human learning processes that emphasize critical thinking, CFT encourages deeper analysis and nuanced understanding-traits often overlooked by standard SFT. To validate the effectiveness of CFT, we construct a 50K-sample dataset from WebInstruct, using GPT-4o as the teacher to generate critiques in the form of (input=[query; noisy response], output=critique). CFT on this dataset yields a consistent 4-10% improvement over SFT on six math benchmarks with different base models like Qwen2.5, Qwen2.5-Math and DeepSeek-Math. We further expand to MetaMath and NuminaMath datasets and observe similar gains over SFT. Notably, our Qwen2.5-Math-CFT model-trained on just 50K samples-matches or outperforms competitive models such as AceMath and Qwen2.5-Math-Instruct on most benchmarks, both of which use over 2M samples. Ablation studies show that CFT is robust to the source of noisy response and teacher critique model. Through these findings, we argue that critique-based training offers a more effective alternative to advance the reasoning of language models.

https://huggingface.co/discussions/paper/679ae770f211c66bd702f697