---
layout: publication
title: 'FILA: Fine-grained Vision Language Models'
authors: Zhu et al.
conference: 2012 Proceedings IEEE INFOCOM
year: 2024
bibkey: zhu2024fila
citations: 286
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2412.08378'}]
tags: [Multimodal Models, RAG, Merging]
---
Recently, there has been growing interest in the capability of multimodal
large language models (MLLMs) to process high-resolution images. A common
approach currently involves dynamically cropping the original high-resolution
image into smaller sub-images, which are then fed into a vision encoder that
was pre-trained on lower-resolution images. However, this cropping approach
often truncates objects and connected areas in the original image, causing
semantic breaks. To address this limitation, we introduce HyViLM, designed to
process images of any resolution while retaining the overall context during
encoding. Specifically, we: (i) Design a new visual encoder called Hybrid
Encoder that not only encodes individual sub-images but also interacts with
detailed global visual features, significantly improving the model's ability to
encode high-resolution images. (ii) Propose an optimal feature fusion strategy
for the dynamic cropping approach, effectively leveraging information from
different layers of the vision encoder. Compared with the state-of-the-art
MLLMs under the same setting, our HyViLM outperforms existing MLLMs in nine out
of ten tasks. Specifically, HyViLM achieves a 9.6% improvement in performance
on the TextVQA task and a 6.9% enhancement on the DocVQA task.