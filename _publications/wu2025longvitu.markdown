---
layout: publication
title: 'Longvitu: Instruction Tuning For Long-form Video Understanding'
authors: Wu et al.
conference: 2021 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2025
bibkey: wu2025longvitu
citations: 85
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2501.05037'}]
tags: [RAG, Training Techniques, GPT, CVPR, Evaluation, Model Architecture, Fine Tuning,
  Datasets]
---
This paper introduces LongViTU, a large-scale (~121k QA pairs, ~900h videos),
automatically generated dataset for long-form video understanding. We propose a
systematic approach that organizes videos into a hierarchical tree structure
for QA generation and incorporates self-revision mechanisms to ensure
high-quality QA pairs. Each QA pair in LongViTU features: 1) long-term context
(average certificate length of 4.6 minutes); 2) rich knowledge and condensed
reasoning (commonsense, causality, planning, etc.)). We also offer explicit
timestamp annotations of relevant events for each QA pair. We have conducted
extensive human studies on LongViTU, and the results prove the quality of our
dataset. To better evaluate the challenges posed by LongViTU's emphasis on
long-term context and condensed reasoning, we manually curate a subset of
LongViTU into a benchmark. Evaluations using a state-of-the-art open-source
model (LongVU), a proprietary model (Gemini-1.5-Pro), and human annotators
yield GPT-4 scores of 49.9, 52.3, and 81.0, respectively, underscoring the
substantial difficulty presented by LongViTU questions. Performing supervised
fine-tuning (SFT) of LongVU and LLaVA-Video on LongViTU data results in average
performance gains of 2.5% and 3.7%, respectively, across a suite of long video
understanding benchmarks (EgoSchema, VideoMME-Long, MLVU, LVBench).