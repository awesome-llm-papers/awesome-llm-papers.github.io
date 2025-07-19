---
layout: publication
title: 'Llm4brain: Training A Large Language Model For Brain Video Understanding'
authors: Zheng Ruizhe, Sun Lichao
conference: 'Findings of the Association for Computational Linguistics: ACL-IJCNLP
  2021'
year: 2024
bibkey: zheng2024llm4brain
citations: 50
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2409.17987'}]
tags: [Fine Tuning, Training Techniques, Evaluation, ACL, Multimodal Models]
---
Decoding visual-semantic information from brain signals, such as functional
MRI (fMRI), across different subjects poses significant challenges, including
low signal-to-noise ratio, limited data availability, and cross-subject
variability. Recent advancements in large language models (LLMs) show
remarkable effectiveness in processing multimodal information. In this study,
we introduce an LLM-based approach for reconstructing visual-semantic
information from fMRI signals elicited by video stimuli. Specifically, we
employ fine-tuning techniques on an fMRI encoder equipped with adaptors to
transform brain responses into latent representations aligned with the video
stimuli. Subsequently, these representations are mapped to textual modality by
LLM. In particular, we integrate self-supervised domain adaptation methods to
enhance the alignment between visual-semantic information and brain responses.
Our proposed method achieves good results using various quantitative semantic
metrics, while yielding similarity with ground-truth information.