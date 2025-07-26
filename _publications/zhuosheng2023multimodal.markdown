---
layout: publication
title: Multimodal Chain-of-thought Reasoning In Language Models
authors: [zhuosheng Zhang, aston Zhang, mu Li, hai Zhao, george Karypis, alex Smola]
conference: Arxiv
year: 2023
bibkey: zhuosheng2023multimodal
citations: 68
additional_links: [{name: Code, url: 'https://github.com/amazon-science/mm-cot'},
  {name: Paper, url: 'http://arxiv.org/abs/2302.00923v5'}]
tags: ["Datasets", "Evaluation", "Has Code", "Prompting", "Tools"]
short_authors: Zhang et al.
---
Large language models (LLMs) have shown impressive performance on complex
reasoning by leveraging chain-of-thought (CoT) prompting to generate
intermediate reasoning chains as the rationale to infer the answer. However,
existing CoT studies have primarily focused on the language modality. We
propose Multimodal-CoT that incorporates language (text) and vision (images)
modalities into a two-stage framework that separates rationale generation and
answer inference. In this way, answer inference can leverage better generated
rationales that are based on multimodal information. Experimental results on
ScienceQA and A-OKVQA benchmark datasets show the effectiveness of our proposed
approach. With Multimodal-CoT, our model under 1 billion parameters achieves
state-of-the-art performance on the ScienceQA benchmark. Our analysis indicates
that Multimodal-CoT offers the advantages of mitigating hallucination and
enhancing convergence speed. Code is publicly available at
https://github.com/amazon-science/mm-cot.