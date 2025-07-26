---
layout: publication
title: 'Fineweb2: One Pipeline To Scale Them All -- Adapting Pre-training Data Processing
  To Every Language'
authors: "Guilherme Penedo, Hynek Kydl\xED\u010Dek, Vinko Sabol\u010Dec, Bettina Messmer,\
  \ Negar Foroutan, Amir Hossein Kargaran, Colin Raffel, Martin Jaggi, Leandro von\
  \ Werra, Thomas Wolf"
conference: No Venue
year: 2025
bibkey: penedo2025fineweb2
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/685de28871131fa43be08a76'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2506.20920'}]
tags: ["Datasets", "Evaluation", "Training Techniques"]
short_authors: Penedo et al.
---
Pre-training state-of-the-art large language models (LLMs) requires vast amounts of clean and diverse text data. While the open development of large high-quality English pre-training datasets has seen substantial recent progress, training performant multilingual LLMs remains a challenge, in large part due to the inherent difficulty of tailoring filtering and deduplication pipelines to a large number of languages. In this work, we introduce a new pre-training dataset curation pipeline based on FineWeb that can be automatically adapted to support any language. We extensively ablate our pipeline design choices on a set of nine diverse languages, guided by a set of meaningful and informative evaluation tasks that were chosen through a novel selection process based on measurable criteria. Ultimately, we show that our pipeline can be used to create non-English corpora that produce more performant models than prior datasets. We additionally introduce a straightforward and principled approach to rebalance datasets that takes into consideration both duplication count and quality, providing an additional performance uplift. Finally, we scale our pipeline to over 1000 languages using almost 100 Common Crawl snapshots to produce FineWeb2, a new 20 terabyte (5 billion document) multilingual dataset which we release along with our pipeline, training, and evaluation codebases.

https://huggingface.co/discussions/paper/685de28871131fa43be08a76