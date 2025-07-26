---
layout: publication
title: 'Mplug-docowl 1.5: Unified Structure Learning For Ocr-free Document Understanding'
authors: Anwen Hu, Haiyang Xu, Jiabo Ye, Ming Yan, Liang Zhang, Bo Zhang, Chen Li,
  Ji Zhang, Qin Jin, Fei Huang, Jingren Zhou
conference: No Venue
year: 2024
bibkey: hu2024mplug
additional_links: [{name: Code, url: 'https://github.com/X-PLUG/mPLUG-DocOwl/tree/main/DocOwl1.5'},
  {name: Code, url: 'https://huggingface.co/discussions/paper/65fa62c5e12a435e55d9ef2d'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2403.12895'}]
tags: ["Training Techniques"]
short_authors: Hu et al.
---
Structure information is critical for understanding the semantics of text-rich images, such as documents, tables, and charts. Existing Multimodal Large Language Models (MLLMs) for Visual Document Understanding are equipped with text recognition ability but lack general structure understanding abilities for text-rich document images. In this work, we emphasize the importance of structure information in Visual Document Understanding and propose the Unified Structure Learning to boost the performance of MLLMs. Our Unified Structure Learning comprises structure-aware parsing tasks and multi-grained text localization tasks across 5 domains: document, webpage, table, chart, and natural image. To better encode structure information, we design a simple and effective vision-to-text module H-Reducer, which can not only maintain the layout information but also reduce the length of visual features by merging horizontal adjacent patches through convolution, enabling the LLM to understand high-resolution images more efficiently. Furthermore, by constructing structure-aware text sequences and multi-grained pairs of texts and bounding boxes for publicly available text-rich images, we build a comprehensive training set DocStruct4M to support structure learning. Finally, we construct a small but high-quality reasoning tuning dataset DocReason25K to trigger the detailed explanation ability in the document domain. Our model DocOwl 1.5 achieves state-of-the-art performance on 10 visual document understanding benchmarks, improving the SOTA performance of MLLMs with a 7B LLM by more than 10 points in 5/10 benchmarks. Our codes, models, and datasets are publicly available at https://github.com/X-PLUG/mPLUG-DocOwl/tree/main/DocOwl1.5.

https://huggingface.co/discussions/paper/65fa62c5e12a435e55d9ef2d