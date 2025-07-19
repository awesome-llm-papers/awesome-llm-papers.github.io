---
layout: publication
title: 'Misaligned Roles, Misplaced Images: Structural Input Perturbations Expose
  Multimodal Alignment Blind Spots'
authors: Shayegani et al.
conference: IEEE Transactions on Image Processing
year: 2025
bibkey: shayegani2025misaligned
citations: 102
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2504.03735'}]
tags: [Training Techniques, Attention Mechanism, Alt, Prompting, Masked Language Model,
  Model Architecture, Security, Multimodal Models, Merging]
---
Multimodal Language Models (MMLMs) typically undergo post-training alignment
to prevent harmful content generation. However, these alignment stages focus
primarily on the assistant role, leaving the user role unaligned, and stick to
a fixed input prompt structure of special tokens, leaving the model vulnerable
when inputs deviate from these expectations. We introduce Role-Modality Attacks
(RMA), a novel class of adversarial attacks that exploit role confusion between
the user and assistant and alter the position of the image token to elicit
harmful outputs. Unlike existing attacks that modify query content, RMAs
manipulate the input structure without altering the query itself. We
systematically evaluate these attacks across multiple Vision Language Models
(VLMs) on eight distinct settings, showing that they can be composed to create
stronger adversarial prompts, as also evidenced by their increased projection
in the negative refusal direction in the residual stream, a property observed
in prior successful attacks. Finally, for mitigation, we propose an adversarial
training approach that makes the model robust against input prompt
perturbations. By training the model on a range of harmful and benign prompts
all perturbed with different RMA settings, it loses its sensitivity to Role
Confusion and Modality Manipulation attacks and is trained to only pay
attention to the content of the query in the input prompt structure,
effectively reducing Attack Success Rate (ASR) while preserving the model's
general utility.