---
layout: publication
title: 'Gecko: Versatile Text Embeddings Distilled From Large Language Models'
authors: Jinhyuk Lee, Zhuyun Dai, Xiaoqi Ren, Blair Chen, Daniel Cer, Jeremy R. Cole,
  Kai Hui, Michael Boratko, Rajvi Kapadia, Wen Ding, Yi Luan, Sai Meher Karthik Duddu,
  Gustavo Hernandez Abrego, Weiqiang Shi, Nithi Gupta, Aditya Kusupati, Prateek Jain,
  Siddhartha Reddy Jonnalagadda, Ming-wei Chang, Iftekhar Naim
conference: No Venue
year: 2024
bibkey: lee2024gecko
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2403.20327'}]
tags: ["Efficiency"]
short_authors: Lee et al.
---
We present Gecko, a compact and versatile text embedding model. Gecko achieves strong retrieval performance by leveraging a key idea: distilling knowledge from large language models (LLMs) into a retriever. Our two-step distillation process begins with generating diverse, synthetic paired data using an LLM. Next, we further refine the data quality by retrieving a set of candidate passages for each query, and relabeling the positive and hard negative passages using the same LLM. The effectiveness of our approach is demonstrated by the compactness of the Gecko. On the Massive Text Embedding Benchmark (MTEB), Gecko with 256 embedding dimensions outperforms all existing entries with 768 embedding size. Gecko with 768 embedding dimensions achieves an average score of 66.31, competing with 7x larger models and 5x higher dimensional embeddings.

https://huggingface.co/discussions/paper/660a3edcdf88d3dbac12ba16