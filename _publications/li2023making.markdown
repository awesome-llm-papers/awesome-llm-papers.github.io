---
layout: publication
title: Making Large Language Models A Better Foundation For Dense Retrieval
authors: Chaofan Li, Zheng Liu, Shitao Xiao, Yingxia Shao
conference: Arxiv
year: 2023
bibkey: li2023making
citations: 82
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2312.15503'}]
tags: ["Has Code"]
short_authors: Li et al.
---
Dense retrieval needs to learn discriminative text embeddings to represent
the semantic relationship between query and document. It may benefit from the
using of large language models (LLMs), given LLMs' strong capability on
semantic understanding. However, the LLMs are pre-trained by text generation
tasks, whose working pattern is completely different from representing texts as
embeddings. As a result, it is imperative to study how to adapt LLMs properly
so that they can be effectively initialized as the backbone encoder for dense
retrieval.
  In this paper, we propose a novel approach, called LLaRA (LLM adapted for
dense RetrievAl), which works as a post-hoc adaptation of LLM for the dense
retrieval application. LLaRA consists of two pretext tasks: EBAE
(Embedding-Based Auto-Encoding) and EBAR (Embedding-Based Auto-Regression),
where the text embeddings from LLM are used to reconstruct the tokens for the
input sentence and predict the tokens for the next sentence, respectively.
LLaRA turns out to be simple, lightweight, and highly effective. It is applied
to adapt LLaMA-2-7B (base) on the Wikipedia corpus, where it substantially
improves the model's fine-tuned performances on a variety of dense retrieval
benchmarks, like MSMARCO and BEIR. Our model and code will be made publicly
available at BGE repository.