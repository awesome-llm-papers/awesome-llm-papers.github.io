---
layout: publication
title: Position-guided Text Prompt For Vision-language Pre-training
authors: Alex Jinpeng Wang, Pan Zhou, Mike Zheng Shou, Shuicheng Yan
conference: 2023 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2022
citations: 18
bibkey: wang2022position
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2212.09737'}, {name: Code,
    url: 'https://github.com/sail-sg/ptp'}]
tags: [Has Code, Model Architecture, RAG, Tools, Multimodal Models, Pre-Training,
  Prompting, Training Techniques, Evaluation]
---
Vision-Language Pre-Training (VLP) has shown promising capabilities to align
image and text pairs, facilitating a broad variety of cross-modal learning
tasks. However, we observe that VLP models often lack the visual
grounding/localization capability which is critical for many downstream tasks
such as visual reasoning. In this work, we propose a novel Position-guided Text
Prompt (PTP) paradigm to enhance the visual grounding ability of cross-modal
models trained with VLP. Specifically, in the VLP phase, PTP divides the image
into \\(N\times N\\) blocks, and identifies the objects in each block through the
widely used object detector in VLP. It then reformulates the visual grounding
task into a fill-in-the-blank problem given a PTP by encouraging the model to
predict the objects in the given blocks or regress the blocks of a given
object, e.g. filling `P" or ``O" in aPTP ``The block P has a O". This mechanism
improves the visual grounding capability of VLP models and thus helps them
better handle various downstream tasks. By introducing PTP into several
state-of-the-art VLP frameworks, we observe consistently significant
improvements across representative cross-modal learning model architectures and
several benchmarks, e.g. zero-shot Flickr30K Retrieval (+4.8 in average
recall@1) for ViLT \cite\{vilt\} baseline, and COCO Captioning (+5.3 in CIDEr)
for SOTA BLIP \cite\{blip\} baseline. Moreover, PTP achieves comparable results
with object-detector based methods, and much faster inference speed since PTP
discards its object detector for inference while the later cannot. Our code and
pre-trained weight will be released at https://github.com/sail-sg/ptp.