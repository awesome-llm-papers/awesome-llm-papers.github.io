---
layout: publication
title: 'Textclip: Text-guided Face Image Generation And Manipulation Without Adversarial
  Training'
authors: You Xiaozhou, Zhang Jian
conference: 2021 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2023
bibkey: you2023textclip
citations: 265
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2309.11923'}]
tags: [Training Techniques, Tools, CVPR, Security, Datasets]
---
Text-guided image generation aimed to generate desired images conditioned on
given texts, while text-guided image manipulation refers to semantically edit
parts of a given image based on specified texts. For these two similar tasks,
the key point is to ensure image fidelity as well as semantic consistency. Many
previous approaches require complex multi-stage generation and adversarial
training, while struggling to provide a unified framework for both tasks. In
this work, we propose TextCLIP, a unified framework for text-guided image
generation and manipulation without adversarial training. The proposed method
accepts input from images or random noise corresponding to these two different
tasks, and under the condition of the specific texts, a carefully designed
mapping network that exploits the powerful generative capabilities of StyleGAN
and the text image representation capabilities of Contrastive Language-Image
Pre-training (CLIP) generates images of up to \\(1024\times1024\\) resolution that
can currently be generated. Extensive experiments on the Multi-modal CelebA-HQ
dataset have demonstrated that our proposed method outperforms existing
state-of-the-art methods, both on text-guided generation tasks and manipulation
tasks.