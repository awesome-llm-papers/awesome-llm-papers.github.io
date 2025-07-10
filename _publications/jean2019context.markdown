---
layout: publication
title: Context-aware Learning For Neural Machine Translation
authors: "S\xE9bastien Jean, Kyunghyun Cho"
conference: Arxiv
year: 2019
citations: 17
bibkey: jean2019context
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1903.04715'}]
tags: [Transformer, RAG, Model Architecture, Evaluation]
---
Interest in larger-context neural machine translation, including
document-level and multi-modal translation, has been growing. Multiple works
have proposed new network architectures or evaluation schemes, but potentially
helpful context is still sometimes ignored by larger-context translation
models. In this paper, we propose a novel learning algorithm that explicitly
encourages a neural translation model to take into account additional context
using a multilevel pair-wise ranking loss. We evaluate the proposed learning
algorithm with a transformer-based larger-context translation system on
document-level translation. By comparing performance using actual and random
contexts, we show that a model trained with the proposed algorithm is more
sensitive to the additional context.