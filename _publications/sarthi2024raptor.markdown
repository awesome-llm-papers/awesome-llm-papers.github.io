---
layout: publication
title: 'RAPTOR: Recursive Abstractive Processing For Tree-organized Retrieval'
authors: Parth Sarthi, Salman Abdullah, Aditi Tuli, Shubh Khanna, Anna Goldie, Christopher
  D. Manning
conference: No Venue
year: 2024
bibkey: sarthi2024raptor
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2401.18059'}]
tags: ["Model Architecture"]
short_authors: Sarthi et al.
---
Retrieval-augmented language models can better adapt to changes in world state and incorporate long-tail knowledge. However, most existing methods retrieve only short contiguous chunks from a retrieval corpus, limiting holistic understanding of the overall document context. We introduce the novel approach of recursively embedding, clustering, and summarizing chunks of text, constructing a tree with differing levels of summarization from the bottom up. At inference time, our RAPTOR model retrieves from this tree, integrating information across lengthy documents at different levels of abstraction. Controlled experiments show that retrieval with recursive summaries offers significant improvements over traditional retrieval-augmented LMs on several tasks. On question-answering tasks that involve complex, multi-step reasoning, we show state-of-the-art results; for example, by coupling RAPTOR retrieval with the use of GPT-4, we can improve the best performance on the QuALITY benchmark by 20% in absolute accuracy.

https://huggingface.co/discussions/paper/65bb083cf8b6408e7f2febb8