---
layout: publication
title: Efficient Medical VIE Via Reinforcement Learning
authors: Lijun Liu, Ruiyang Li, Zhaocheng Liu, Chenglin Zhu, Chong Li, Jiehan Cheng,
  Qiang Ju, Jian Xie
conference: No Venue
year: 2025
bibkey: liu2025efficient
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/685234100164cd1316710510'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2506.13363'}]
tags: ["Applications", "Efficiency", "Reinforcement Learning"]
short_authors: Liu et al.
---
Visual Information Extraction (VIE) converts unstructured document images into structured formats like JSON, critical for medical applications such as report analysis and online consultations. Traditional methods rely on OCR and language models, while end-to-end multimodal models offer direct JSON generation. However, domain-specific schemas and high annotation costs limit their effectiveness in medical VIE. We base our approach on the Reinforcement Learning with Verifiable Rewards (RLVR) framework to address these challenges using only 100 annotated samples. Our approach ensures dataset diversity, a balanced precision-recall reward mechanism to reduce hallucinations and improve field coverage, and innovative sampling strategies to enhance reasoning capabilities. Fine-tuning Qwen2.5-VL-7B with our RLVR method, we achieve state-of-the-art performance on medical VIE tasks, significantly improving F1, precision, and recall. While our models excel on tasks similar to medical datasets, performance drops on dissimilar tasks, highlighting the need for domain-specific optimization. Case studies further demonstrate the value of reasoning during training and inference for VIE.

https://huggingface.co/discussions/paper/685234100164cd1316710510