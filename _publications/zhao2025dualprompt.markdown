---
layout: publication
title: 'Dualprompt-medcap: A Dual-prompt Enhanced Approach For Medical Image Captioning'
authors: Zhao Yining, Braytee Ali, Prasad Mukesh
conference: Neural Networks
year: 2025
bibkey: zhao2025dualprompt
citations: 88
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2504.09598'}]
tags: [RAG, Training Techniques, ICANN, Prompting, Tools, Evaluation, Multimodal Models,
  Datasets]
---
Medical image captioning via vision-language models has shown promising
potential for clinical diagnosis assistance. However, generating contextually
relevant descriptions with accurate modality recognition remains challenging.
We present DualPrompt-MedCap, a novel dual-prompt enhancement framework that
augments Large Vision-Language Models (LVLMs) through two specialized
components: (1) a modality-aware prompt derived from a semi-supervised
classification model pretrained on medical question-answer pairs, and (2) a
question-guided prompt leveraging biomedical language model embeddings. To
address the lack of captioning ground truth, we also propose an evaluation
framework that jointly considers spatial-semantic relevance and medical
narrative quality. Experiments on multiple medical datasets demonstrate that
DualPrompt-MedCap outperforms the baseline BLIP-3 by achieving a 22%
improvement in modality recognition accuracy while generating more
comprehensive and question-aligned descriptions. Our method enables the
generation of clinically accurate reports that can serve as medical experts'
prior knowledge and automatic annotations for downstream vision-language tasks.