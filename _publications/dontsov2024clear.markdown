---
layout: publication
title: 'CLEAR: Character Unlearning In Textual And Visual Modalities'
authors: Alexey Dontsov, Dmitrii Korzh, Alexey Zhavoronkin, Boris Mikheev, Denis Bobkov,
  Aibek Alanov, Oleg Y. Rogov, Ivan Oseledets, Elena Tutubalina
conference: No Venue
year: 2024
bibkey: dontsov2024clear
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2410.18057'}]
tags: ["Datasets", "Evaluation", "Fine-Tuning", "Privacy", "Security"]
short_authors: Dontsov et al.
---
Machine Unlearning (MU) is critical for enhancing privacy and security in deep learning models, particularly in large multimodal language models (MLLMs), by removing specific private or hazardous information. While MU has made significant progress in textual and visual modalities, multimodal unlearning (MMU) remains significantly underexplored, partially due to the absence of a suitable open-source benchmark. To address this, we introduce CLEAR, a new benchmark designed to evaluate MMU methods. CLEAR contains 200 fictitious individuals and 3,700 images linked with corresponding question-answer pairs, enabling a thorough evaluation across modalities. We assess 10 MU methods, adapting them for MMU, and highlight new challenges specific to multimodal forgetting. We also demonstrate that simple ell_1 regularization on LoRA weights significantly mitigates catastrophic forgetting, preserving model performance on retained data. The dataset is available at https://huggingface.co/datasets/therem/CLEAR

https://huggingface.co/discussions/paper/671a4318a7873ff9b21ceb14