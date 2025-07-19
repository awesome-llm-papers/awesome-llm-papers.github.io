---
layout: publication
title: Visual Question Generation As Dual Task Of Visual Question Answering
authors: Li et al.
conference: 2018 IEEE/CVF Conference on Computer Vision and Pattern Recognition
year: 2017
bibkey: li2017visual
citations: 177
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1709.07192'}]
tags: [RAG, Training Techniques, Tools, CVPR, Model Architecture, Datasets]
---
Recently visual question answering (VQA) and visual question generation (VQG)
are two trending topics in the computer vision, which have been explored
separately. In this work, we propose an end-to-end unified framework, the
Invertible Question Answering Network (iQAN), to leverage the complementary
relations between questions and answers in images by jointly training the model
on VQA and VQG tasks. Corresponding parameter sharing scheme and regular terms
are proposed as constraints to explicitly leverage Q,A's dependencies to guide
the training process. After training, iQAN can take either question or answer
as input, then output the counterpart. Evaluated on the large-scale visual
question answering datasets CLEVR and VQA2, our iQAN improves the VQA accuracy
over the baselines. We also show the dual learning framework of iQAN can be
generalized to other VQA architectures and consistently improve the results
over both the VQA and VQG tasks.