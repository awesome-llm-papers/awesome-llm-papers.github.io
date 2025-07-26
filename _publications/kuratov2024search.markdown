---
layout: publication
title: 'In Search Of Needles In A 10M Haystack: Recurrent Memory Finds What Llms Miss'
authors: Yuri Kuratov, Aydar Bulatov, Petr Anokhin, Dmitry Sorokin, Artyom Sorokin,
  Mikhail Burtsev
conference: No Venue
year: 2024
bibkey: kuratov2024search
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2402.10790'}]
tags: ["RAG"]
short_authors: Kuratov et al.
---
This paper addresses the challenge of processing long documents using generative transformer models. To evaluate different approaches, we introduce BABILong, a new benchmark designed to assess model capabilities in extracting and processing distributed facts within extensive texts. Our evaluation, which includes benchmarks for GPT-4 and RAG, reveals that common methods are effective only for sequences up to 10^4 elements. In contrast, fine-tuning GPT-2 with recurrent memory augmentations enables it to handle tasks involving up to 10^7 elements. This achievement marks a substantial leap, as it is by far the longest input processed by any open neural network model to date, demonstrating a significant improvement in the processing capabilities for long sequences.

https://huggingface.co/discussions/paper/65d2d4b86f1a8bf6a1a09c67