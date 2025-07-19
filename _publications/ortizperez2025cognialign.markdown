---
layout: publication
title: 'Cognialign: Word-level Multimodal Speech Alignment With Gated Cross-attention
  For Alzheimer''s Detection'
authors: Ortiz-perez et al.
conference: 'Proceedings of the 56th Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)'
year: 2025
bibkey: ortizperez2025cognialign
citations: 105
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2506.01890'}]
tags: [Model Architecture, Merging, ACL, RAG, Multimodal Models, Datasets, Reinforcement
    Learning, Attention Mechanism, Alt]
---
Early detection of cognitive disorders such as Alzheimer's disease is critical for enabling timely clinical intervention and improving patient outcomes. In this work, we introduce CogniAlign, a multimodal architecture for Alzheimer's detection that integrates audio and textual modalities, two non-intrusive sources of information that offer complementary insights into cognitive health. Unlike prior approaches that fuse modalities at a coarse level, CogniAlign leverages a word-level temporal alignment strategy that synchronizes audio embeddings with corresponding textual tokens based on transcription timestamps. This alignment supports the development of token-level fusion techniques, enabling more precise cross-modal interactions. To fully exploit this alignment, we propose a Gated Cross-Attention Fusion mechanism, where audio features attend over textual representations, guided by the superior unimodal performance of the text modality. In addition, we incorporate prosodic cues, specifically interword pauses, by inserting pause tokens into the text and generating audio embeddings for silent intervals, further enriching both streams. We evaluate CogniAlign on the ADReSSo dataset, where it achieves an accuracy of 90.36%, outperforming existing state-of-the-art methods. A detailed ablation study confirms the advantages of our alignment strategy, attention-based fusion, and prosodic modeling.