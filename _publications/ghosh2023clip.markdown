---
layout: publication
title: 'Clipsyntel: CLIP And LLM Synergy For Multimodal Question Summarization In
  Healthcare'
authors: Akash Ghosh et al.
conference: Arxiv
year: 2023
citations: 15
bibkey: ghosh2023clip
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2312.11541'}]
tags: [Training Techniques, RAG, Tools, Multimodal Models, Language Modeling]
---
In the era of modern healthcare, swiftly generating medical question
summaries is crucial for informed and timely patient care. Despite the
increasing complexity and volume of medical data, existing studies have focused
solely on text-based summarization, neglecting the integration of visual
information. Recognizing the untapped potential of combining textual queries
with visual representations of medical conditions, we introduce the Multimodal
Medical Question Summarization (MMQS) Dataset. This dataset, a major
contribution to our work, pairs medical queries with visual aids, facilitating
a richer and more nuanced understanding of patient needs. We also propose a
framework, utilizing the power of Contrastive Language Image Pretraining(CLIP)
and Large Language Models(LLMs), consisting of four modules that identify
medical disorders, generate relevant context, filter medical concepts, and
craft visually aware summaries. Our comprehensive framework harnesses the power
of CLIP, a multimodal foundation model, and various general-purpose LLMs,
comprising four main modules: the medical disorder identification module, the
relevant context generation module, the context filtration module for
distilling relevant medical concepts and knowledge, and finally, a
general-purpose LLM to generate visually aware medical question summaries.
Leveraging our MMQS dataset, we showcase how visual cues from images enhance
the generation of medically nuanced summaries. This multimodal approach not
only enhances the decision-making process in healthcare but also fosters a more
nuanced understanding of patient queries, laying the groundwork for future
research in personalized and responsive medical care