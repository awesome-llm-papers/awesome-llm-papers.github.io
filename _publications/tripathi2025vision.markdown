---
layout: publication
title: 'Vision-guided Chunking Is All You Need: Enhancing RAG With Multimodal Document
  Understanding'
authors: Vishesh Tripathi, Tanmay Odapally, Indraneel Das, Uday Allu, Biddwan Ahmed
conference: No Venue
year: 2025
bibkey: tripathi2025vision
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2506.16035'}]
tags: ["RAG"]
short_authors: Tripathi et al.
---
Retrieval-Augmented Generation (RAG) systems have revolutionized information retrieval and question answering, but traditional text-based chunking methods struggle with complex document structures, multi-page tables, embedded figures, and contextual dependencies across page boundaries. We present a novel multimodal document chunking approach that leverages Large Multimodal Models (LMMs) to process PDF documents in batches while maintaining semantic coherence and structural integrity. Our method processes documents in configurable page batches with cross-batch context preservation, enabling accurate handling of tables spanning multiple pages, embedded visual elements, and procedural content. We evaluate our approach on a curated dataset of PDF documents with manually crafted queries, demonstrating improvements in chunk quality and downstream RAG performance. Our vision-guided approach achieves better accuracy compared to traditional vanilla RAG systems, with qualitative analysis showing superior preservation of document structure and semantic coherence.

https://huggingface.co/discussions/paper/6858d76cc0c8e29df8ea3ce0