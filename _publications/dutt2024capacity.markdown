---
layout: publication
title: Capacity Control Is An Effective Memorization Mitigation Mechanism In Text-conditional
  Diffusion Models
authors: Dutt et al.
conference: 2023 IEEE/CVF International Conference on Computer Vision (ICCV)
year: 2024
bibkey: dutt2024capacity
citations: 1788
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2410.22149'}]
tags: [ICCV, Training Techniques, Evaluation, Fine Tuning, Datasets, Merging]
---
In this work, we present compelling evidence that controlling model capacity
during fine-tuning can effectively mitigate memorization in diffusion models.
Specifically, we demonstrate that adopting Parameter-Efficient Fine-Tuning
(PEFT) within the pre-train fine-tune paradigm significantly reduces
memorization compared to traditional full fine-tuning approaches. Our
experiments utilize the MIMIC dataset, which comprises image-text pairs of
chest X-rays and their corresponding reports. The results, evaluated through a
range of memorization and generation quality metrics, indicate that PEFT not
only diminishes memorization but also enhances downstream generation quality.
Additionally, PEFT methods can be seamlessly combined with existing
memorization mitigation techniques for further improvement. The code for our
experiments is available at:
https://github.com/Raman1121/Diffusion_Memorization_HPO