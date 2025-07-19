---
layout: publication
title: Benchmarking Large Vision-language Models Via Directed Scene Graph For Comprehensive
  Image Captioning
authors: Lu et al.
conference: Lecture Notes in Computer Science
year: 2024
bibkey: lu2024benchmarking
citations: 77
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2412.08614'}]
tags: [RAG, Attention Mechanism, Evaluation, Model Architecture, Multimodal Models,
  Datasets]
---
Generating detailed captions comprehending text-rich visual content in images
has received growing attention for Large Vision-Language Models (LVLMs).
However, few studies have developed benchmarks specifically tailored for
detailed captions to measure their accuracy and comprehensiveness. In this
paper, we introduce a detailed caption benchmark, termed as CompreCap, to
evaluate the visual context from a directed scene graph view. Concretely, we
first manually segment the image into semantically meaningful regions (i.e.,
semantic segmentation mask) according to common-object vocabulary, while also
distinguishing attributes of objects within all those regions. Then directional
relation labels of these objects are annotated to compose a directed scene
graph that can well encode rich compositional information of the image. Based
on our directed scene graph, we develop a pipeline to assess the generated
detailed captions from LVLMs on multiple levels, including the object-level
coverage, the accuracy of attribute descriptions, the score of key
relationships, etc. Experimental results on the CompreCap dataset confirm that
our evaluation method aligns closely with human evaluation scores across LVLMs.