---
layout: publication
title: Masked Generative Story Transformer With Character Guidance And Caption Augmentation
authors: Papadimitriou et al.
conference: 2023 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2024
bibkey: papadimitriou2024masked
citations: 63
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2403.08502'}]
tags: [Attention Mechanism, Evaluation, CVPR, Transformer, Model Architecture, Survey
    Paper, Reinforcement Learning, Security, Datasets]
---
Story Visualization (SV) is a challenging generative vision task, that
requires both visual quality and consistency between different frames in
generated image sequences. Previous approaches either employ some kind of
memory mechanism to maintain context throughout an auto-regressive generation
of the image sequence, or model the generation of the characters and their
background separately, to improve the rendering of characters. On the contrary,
we embrace a completely parallel transformer-based approach, exclusively
relying on Cross-Attention with past and future captions to achieve
consistency. Additionally, we propose a Character Guidance technique to focus
on the generation of characters in an implicit manner, by forming a combination
of text-conditional and character-conditional logits in the logit space. We
also employ a caption-augmentation technique, carried out by a Large Language
Model (LLM), to enhance the robustness of our approach. The combination of
these methods culminates into state-of-the-art (SOTA) results over various
metrics in the most prominent SV benchmark (Pororo-SV), attained with
constraint resources while achieving superior computational complexity compared
to previous arts. The validity of our quantitative results is supported by a
human survey.