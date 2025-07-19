---
layout: publication
title: 'Reconstruct Before Query: Continual Missing Modality Learning With Decomposed
  Prompt Collaboration'
authors: Zhao et al.
conference: 2023 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2024
bibkey: zhao2024reconstruct
citations: 127
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2403.11373'}]
tags: [RAG, Training Techniques, Prompting, Tools, CVPR, Evaluation, Applications,
  Fine Tuning, Datasets]
---
Pre-trained large multi-modal models (LMMs) exploit fine-tuning to adapt
diverse user applications. Nevertheless, fine-tuning may face challenges due to
deactivated sensors (e.g., cameras turned off for privacy or technical issues),
yielding modality-incomplete data and leading to inconsistency in training data
and the data for inference. Additionally, continuous training leads to
catastrophic forgetting, diluting the knowledge in pre-trained LMMs. To
overcome these challenges, we introduce a novel task, Continual Missing
Modality Learning (CMML), to investigate how models can generalize when data of
certain modalities is missing during continual fine-tuning. Our preliminary
benchmarks reveal that existing methods suffer from a significant performance
drop in CMML, even with the aid of advanced continual learning techniques.
Therefore, we devise a framework termed Reconstruct before Query (RebQ). It
decomposes prompts into modality-specific ones and breaks them into components
stored in pools accessible via a key-query mechanism, which facilitates
ParameterEfficient Fine-Tuning and enhances knowledge transferability for
subsequent tasks. Meanwhile, our RebQ leverages extensive multi-modal knowledge
from pre-trained LMMs to reconstruct the data of missing modality.
Comprehensive experiments demonstrate that RebQ effectively reconstructs the
missing modality information and retains pre-trained knowledge. Specifically,
compared with the baseline, RebQ improves average precision from 20.00 to 50.92
and decreases average forgetting from 75.95 to 8.56. Code and datasets are
available on https://github.com/Tree-Shu-Zhao/RebQ.pytorch