---
layout: publication
title: Multimodal Medical Image Binding Via Shared Text Embeddings
authors: Liu et al.
conference: 2019 IEEE/CVF International Conference on Computer Vision (ICCV)
year: 2025
bibkey: liu2025multimodal
citations: 60
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2506.18072'}]
tags: [ICCV, Training Techniques, Tools, Few Shot, Multimodal Models]
---
Medical image analysis increasingly relies on the integration of multiple imaging modalities to capture complementary anatomical and functional information, enabling more accurate diagnosis and treatment planning. Achieving aligned feature representations across these diverse modalities is therefore important for effective multimodal analysis. While contrastive language-image pre-training (CLIP) and its variant have enabled image-text alignments, they require explicitly paired data between arbitrary two modalities, which is difficult to acquire in medical contexts. To address the gap, we present Multimodal Medical Image Binding with Text (M\textsuperscript\{3\}Bind), a novel pre-training framework that enables seamless alignment of multiple medical imaging modalities through a shared text representation space without requiring explicit paired data between any two medical image modalities. Specifically, based on the insight that different images can naturally bind with text, M\textsuperscript\{3\}Bind first fine-tunes pre-trained CLIP-like image-text models to align their modality-specific text embedding space while preserving their original image-text alignments. Subsequently, we distill these modality-specific text encoders into a unified model, creating a shared text embedding space. Experiments on X-ray, CT, retina, ECG, and pathological images on multiple downstream tasks demonstrate that M\textsuperscript\{3\}Bind achieves state-of-the-art performance in zero-shot, few-shot classification and cross-modal retrieval tasks compared to its CLIP-like counterparts. These results validate M\textsuperscript\{3\}Bind's effectiveness in achieving cross-image-modal alignment for medical analysis.