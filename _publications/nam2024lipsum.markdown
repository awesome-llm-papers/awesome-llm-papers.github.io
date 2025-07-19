---
layout: publication
title: 'Lipsum-ft: Robust Fine-tuning Of Zero-shot Models Using Random Text Guidance'
authors: Nam Giung, Heo Byeongho, Lee Juho
conference: 2022 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2024
bibkey: nam2024lipsum
citations: 230
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2404.00860'}]
tags: [Training Techniques, CVPR, Security, Fine Tuning, Multimodal Models]
---
Large-scale contrastive vision-language pre-trained models provide the
zero-shot model achieving competitive performance across a range of image
classification tasks without requiring training on downstream data. Recent
works have confirmed that while additional fine-tuning of the zero-shot model
on the reference data results in enhanced downstream performance, it
compromises the model's robustness against distribution shifts. Our
investigation begins by examining the conditions required to achieve the goals
of robust fine-tuning, employing descriptions based on feature distortion
theory and joint energy-based models. Subsequently, we propose a novel robust
fine-tuning algorithm, Lipsum-FT, that effectively utilizes the language
modeling aspect of the vision-language pre-trained models. Extensive
experiments conducted on distribution shift scenarios in DomainNet and ImageNet
confirm the superiority of our proposed Lipsum-FT approach over existing robust
fine-tuning methods.