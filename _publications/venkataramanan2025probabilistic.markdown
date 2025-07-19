---
layout: publication
title: 'Probabilistic Embeddings For Frozen Vision-language Models: Uncertainty Quantification
  With Gaussian Process Latent Variable Models'
authors: Venkataramanan Aishwarya, Bodesheim Paul, Denzler Joachim
conference: Proceedings of the 24th international conference on Machine learning
year: 2025
bibkey: venkataramanan2025probabilistic
citations: 106
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2505.05163'}]
tags: [RAG, Training Techniques, Evaluation, ICML, Multimodal Models, Datasets]
---
Vision-Language Models (VLMs) learn joint representations by mapping images and text into a shared latent space. However, recent research highlights that deterministic embeddings from standard VLMs often struggle to capture the uncertainties arising from the ambiguities in visual and textual descriptions and the multiple possible correspondences between images and texts. Existing approaches tackle this by learning probabilistic embeddings during VLM training, which demands large datasets and does not leverage the powerful representations already learned by large-scale VLMs like CLIP. In this paper, we propose GroVE, a post-hoc approach to obtaining probabilistic embeddings from frozen VLMs. GroVE builds on Gaussian Process Latent Variable Model (GPLVM) to learn a shared low-dimensional latent space where image and text inputs are mapped to a unified representation, optimized through single-modal embedding reconstruction and cross-modal alignment objectives. Once trained, the Gaussian Process model generates uncertainty-aware probabilistic embeddings. Evaluation shows that GroVE achieves state-of-the-art uncertainty calibration across multiple downstream tasks, including cross-modal retrieval, visual question answering, and active learning.