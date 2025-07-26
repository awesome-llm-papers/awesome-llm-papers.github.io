---
layout: publication
title: 'Mmdocir: Benchmarking Multi-modal Retrieval For Long Documents'
authors: Kuicai Dong, Yujing Chang, Xin Deik Goh, Dexun Li, Ruiming Tang, Yong Liu
conference: No Venue
year: 2025
bibkey: dong2025mmdocir
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2501.08828'}]
tags: ["Datasets", "Evaluation"]
short_authors: Dong et al.
---
Multi-modal document retrieval is designed to identify and retrieve various forms of multi-modal content, such as figures, tables, charts, and layout information from extensive documents. Despite its significance, there is a notable lack of a robust benchmark to effectively evaluate the performance of systems in multi-modal document retrieval. To address this gap, this work introduces a new benchmark, named as MMDocIR, encompassing two distinct tasks: page-level and layout-level retrieval. The former focuses on localizing the most relevant pages within a long document, while the latter targets the detection of specific layouts, offering a more fine-grained granularity than whole-page analysis. A layout can refer to a variety of elements such as textual paragraphs, equations, figures, tables, or charts. The MMDocIR benchmark comprises a rich dataset featuring expertly annotated labels for 1,685 questions and bootstrapped labels for 173,843 questions, making it a pivotal resource for advancing multi-modal document retrieval for both training and evaluation. Through rigorous experiments, we reveal that (i) visual retrievers significantly outperform their text counterparts, (ii) MMDocIR train set can effectively benefit the training process of multi-modal document retrieval and (iii) text retrievers leveraging on VLM-text perform much better than those using OCR-text. These findings underscores the potential advantages of integrating visual elements for multi-modal document retrieval.

https://huggingface.co/discussions/paper/67889539383254ec3f017a72