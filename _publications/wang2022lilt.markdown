---
layout: publication
title: 'Lilt: A Simple Yet Effective Language-independent Layout Transformer For Structured
  Document Understanding'
authors: Jiapeng Wang, Lianwen Jin, Kai Ding
conference: 'Proceedings of the 60th Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)'
year: 2022
bibkey: wang2022lilt
citations: 92
additional_links: [{name: Code, url: 'https://github.com/jpWang/LiLT'}, {name: Paper,
    url: 'https://arxiv.org/abs/2202.13669'}]
tags: ["Model Architecture"]
short_authors: Jiapeng Wang, Lianwen Jin, Kai Ding
---
Structured document understanding has attracted considerable attention and
made significant progress recently, owing to its crucial role in intelligent
document processing. However, most existing related models can only deal with
the document data of specific language(s) (typically English) included in the
pre-training collection, which is extremely limited. To address this issue, we
propose a simple yet effective Language-independent Layout Transformer (LiLT)
for structured document understanding. LiLT can be pre-trained on the
structured documents of a single language and then directly fine-tuned on other
languages with the corresponding off-the-shelf monolingual/multilingual
pre-trained textual models. Experimental results on eight languages have shown
that LiLT can achieve competitive or even superior performance on diverse
widely-used downstream benchmarks, which enables language-independent benefit
from the pre-training of document layout structure. Code and model are publicly
available at https://github.com/jpWang/LiLT.