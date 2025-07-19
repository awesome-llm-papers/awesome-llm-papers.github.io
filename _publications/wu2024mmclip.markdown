---
layout: publication
title: 'MMCLIP: Cross-modal Attention Masked Modelling For Medical Language-image
  Pre-training'
authors: Wu et al.
conference: Lecture Notes in Computer Science
year: 2024
bibkey: wu2024mmclip
citations: 72
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2407.19546'}]
tags: [Training Techniques, Attention Mechanism, Prompting, Masked Language Model,
  Tools, BERT, Model Architecture, Efficiency And Optimization, Language Modeling,
  Fine Tuning, Multimodal Models, Datasets]
---
Vision-and-language pretraining (VLP) in the medical field utilizes
contrastive learning on image-text pairs to achieve effective transfer across
tasks. Yet, current VLP approaches with the masked modeling strategy face two
challenges when applied to the medical domain. First, current models struggle
to accurately reconstruct key pathological features due to the scarcity of
medical data. Second, most methods only adopt either paired image-text or
image-only data, failing to exploit the combination of both paired and unpaired
data. To this end, this paper proposes the MMCLIP (Masked Medical Contrastive
Language-Image Pre-Training) framework to enhance pathological learning and
feature learning via unpaired data. First, we introduce the attention-masked
image modeling (AttMIM) and entity-driven masked language modeling module
(EntMLM), which learns to reconstruct pathological visual and textual tokens
via multi-modal feature interaction, thus improving medical-enhanced features.
The AttMIM module masks a portion of the image features that are highly
responsive to textual features. This allows MMCLIP to improve the
reconstruction of highly similar image data in medicine efficiency. Second, our
MMCLIP capitalizes unpaired data to enhance multimodal learning by introducing
disease-kind prompts. The experimental results show that MMCLIP achieves SOTA
for zero-shot and fine-tuning classification performance on five datasets. Our
code will be available at https://github.com/AIGeeksGroup/MMCLIP.