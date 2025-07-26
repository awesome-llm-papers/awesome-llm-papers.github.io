---
layout: publication
title: 'LMDX: Language Model-based Document Information Extraction And Localization'
authors: Vincent Perot, Kai Kang, Florian Luisier, Guolong Su, Xiaoyu Sun, Ramya Sree
  Boppana, Zilong Wang, Jiaqi Mu, Hao Zhang, Nan Hua
conference: No Venue
year: 2023
bibkey: perot2023lmdx
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2309.10952'}]
tags: ["Training Techniques"]
short_authors: Perot et al.
---
Large Language Models (LLM) have revolutionized Natural Language Processing (NLP), improving state-of-the-art on many existing tasks and exhibiting emergent capabilities. However, LLMs have not yet been successfully applied on semi-structured document information extraction, which is at the core of many document processing workflows and consists of extracting key entities from a visually rich document (VRD) given a predefined target schema. The main obstacles to LLM adoption in that task have been the absence of layout encoding within LLMs, critical for a high quality extraction, and the lack of a grounding mechanism ensuring the answer is not hallucinated. In this paper, we introduce Language Model-based Document Information Extraction and Localization (LMDX), a methodology to adapt arbitrary LLMs for document information extraction. LMDX can do extraction of singular, repeated, and hierarchical entities, both with and without training data, while providing grounding guarantees and localizing the entities within the document. In particular, we apply LMDX to the PaLM 2-S LLM and evaluate it on VRDU and CORD benchmarks, setting a new state-of-the-art and showing how LMDX enables the creation of high quality, data-efficient parsers.

https://huggingface.co/discussions/paper/650ba3e812c086ce18bcd379