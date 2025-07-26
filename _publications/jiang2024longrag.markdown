---
layout: publication
title: 'Longrag: Enhancing Retrieval-augmented Generation With Long-context Llms'
authors: Ziyan Jiang, Xueguang Ma, Wenhu Chen
conference: No Venue
year: 2024
bibkey: jiang2024longrag
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2406.15319'}]
tags: ["RAG", "Retrieval Systems", "Training Techniques"]
short_authors: Ziyan Jiang, Xueguang Ma, Wenhu Chen
---
In traditional RAG framework, the basic retrieval units are normally short. The common retrievers like DPR normally work with 100-word Wikipedia paragraphs. Such a design forces the retriever to search over a large corpus to find the `needle' unit. In contrast, the readers only need to extract answers from the short retrieved units. Such an imbalanced `heavy' retriever and `light' reader design can lead to sub-optimal performance. In order to alleviate the imbalance, we propose a new framework LongRAG, consisting of a `long retriever' and a `long reader'. LongRAG processes the entire Wikipedia into 4K-token units, which is 30x longer than before. By increasing the unit size, we significantly reduce the total units from 22M to 700K. This significantly lowers the burden of retriever, which leads to a remarkable retrieval score: answer recall@1=71% on NQ (previously 52%) and answer recall@2=72% (previously 47%) on HotpotQA (full-wiki). Then we feed the top-k retrieved units (approx 30K tokens) to an existing long-context LLM to perform zero-shot answer extraction. Without requiring any training, LongRAG achieves an EM of 62.7% on NQ, which is the best known result. LongRAG also achieves 64.3% on HotpotQA (full-wiki), which is on par of the SoTA model. Our study offers insights into the future roadmap for combining RAG with long-context LLMs.

https://huggingface.co/discussions/paper/6678e77d66539bc0a08db1f4