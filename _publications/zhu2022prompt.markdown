---
layout: publication
title: Prompt-aligned Gradient For Prompt Tuning
authors: Beier Zhu, Yulei Niu, Yucheng Han, Yue Wu, Hanwang Zhang
conference: 2023 IEEE/CVF International Conference on Computer Vision (ICCV)
year: 2022
citations: 104
bibkey: zhu2022prompt
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2205.14865'}, {name: Code,
    url: 'https://github.com/BeierZhu/Prompt-align'}]
tags: [Has Code, Fine-Tuning, Few-Shot, Reinforcement Learning, Multimodal Models,
  Prompting, Training Techniques]
---
Thanks to the large pre-trained vision-language models (VLMs) like CLIP, we
can craft a zero-shot classifier by "prompt", e.g., the confidence score of an
image being "[CLASS]" can be obtained by using the VLM provided similarity
measure between the image and the prompt sentence "a photo of a [CLASS]".
Therefore, prompt shows a great potential for fast adaptation of VLMs to
downstream tasks if we fine-tune the prompt-based similarity measure. However,
we find a common failure that improper fine-tuning may not only undermine the
prompt's inherent prediction for the task-related classes, but also for other
classes in the VLM vocabulary. Existing methods still address this problem by
using traditional anti-overfitting techniques such as early stopping and data
augmentation, which lack a principled solution specific to prompt. We present
Prompt-aligned Gradient, dubbed ProGrad, to prevent prompt tuning from
forgetting the the general knowledge learned from VLMs. In particular, ProGrad
only updates the prompt whose gradient is aligned (or non-conflicting) to the
"general direction", which is represented as the gradient of the KL loss of the
pre-defined prompt prediction. Extensive experiments demonstrate the stronger
few-shot generalization ability of ProGrad over state-of-the-art prompt tuning
methods. Codes are available at https://github.com/BeierZhu/Prompt-align.