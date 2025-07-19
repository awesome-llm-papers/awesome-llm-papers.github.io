---
layout: publication
title: Multimodal Whole Slide Foundation Model For Pathology
authors: Ding et al.
conference: Nature
year: 2024
bibkey: ding2024multimodal
citations: 188
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2411.19666'}]
tags: [Multimodal Models, Few Shot, Training Techniques]
---
The field of computational pathology has been transformed with recent
advances in foundation models that encode histopathology region-of-interests
(ROIs) into versatile and transferable feature representations via
self-supervised learning (SSL). However, translating these advancements to
address complex clinical challenges at the patient and slide level remains
constrained by limited clinical data in disease-specific cohorts, especially
for rare clinical conditions. We propose TITAN, a multimodal whole slide
foundation model pretrained using 335,645 WSIs via visual self-supervised
learning and vision-language alignment with corresponding pathology reports and
423,122 synthetic captions generated from a multimodal generative AI copilot
for pathology. Without any finetuning or requiring clinical labels, TITAN can
extract general-purpose slide representations and generate pathology reports
that generalize to resource-limited clinical scenarios such as rare disease
retrieval and cancer prognosis. We evaluate TITAN on diverse clinical tasks and
find that TITAN outperforms both ROI and slide foundation models across machine
learning settings such as linear probing, few-shot and zero-shot
classification, rare cancer retrieval and cross-modal retrieval, and pathology
report generation.