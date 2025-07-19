---
layout: publication
title: 'XAIQA: Explainer-based Data Augmentation For Extractive Question Answering'
authors: Stremmel et al.
conference: Proceedings of the 10th International Conference on Natural Language Generation
year: 2023
bibkey: stremmel2023xaiqa
citations: 66
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2312.03567'}]
tags: [GPT, Alt, Prompting, Evaluation, Transformer, Model Architecture]
---
Extractive question answering (QA) systems can enable physicians and
researchers to query medical records, a foundational capability for designing
clinical studies and understanding patient medical history. However, building
these systems typically requires expert-annotated QA pairs. Large language
models (LLMs), which can perform extractive QA, depend on high quality data in
their prompts, specialized for the application domain. We introduce a novel
approach, XAIQA, for generating synthetic QA pairs at scale from data naturally
available in electronic health records. Our method uses the idea of a
classification model explainer to generate questions and answers about medical
concepts corresponding to medical codes. In an expert evaluation with two
physicians, our method identifies \\(2.2\times\\) more semantic matches and
\\(3.8\times\\) more clinical abbreviations than two popular approaches that use
sentence transformers to create QA pairs. In an ML evaluation, adding our QA
pairs improves performance of GPT-4 as an extractive QA model, including on
difficult questions. In both the expert and ML evaluations, we examine
trade-offs between our method and sentence transformers for QA pair generation
depending on question difficulty.