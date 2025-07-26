---
layout: publication
title: Multimodal Memory Modelling For Video Captioning
authors: Junbo Wang, Wei Wang, Yan Huang, Liang Wang, Tieniu Tan
conference: 2018 IEEE/CVF Conference on Computer Vision and Pattern Recognition
year: 2018
bibkey: wang2016multimodal
citations: 168
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1611.05592'}]
tags: ["CVPR", "Datasets", "Evaluation", "Memory & Context", "Model Architecture"]
short_authors: Wang et al.
---
Video captioning which automatically translates video clips into natural
language sentences is a very important task in computer vision. By virtue of
recent deep learning technologies, e.g., convolutional neural networks (CNNs)
and recurrent neural networks (RNNs), video captioning has made great progress.
However, learning an effective mapping from visual sequence space to language
space is still a challenging problem. In this paper, we propose a Multimodal
Memory Model (M3) to describe videos, which builds a visual and textual shared
memory to model the long-term visual-textual dependency and further guide
global visual attention on described targets. Specifically, the proposed M3
attaches an external memory to store and retrieve both visual and textual
contents by interacting with video and sentence with multiple read and write
operations. First, text representation in the Long Short-Term Memory (LSTM)
based text decoder is written into the memory, and the memory contents will be
read out to guide an attention to select related visual targets. Then, the
selected visual information is written into the memory, which will be further
read out to the text decoder. To evaluate the proposed model, we perform
experiments on two publicly benchmark datasets: MSVD and MSR-VTT. The
experimental results demonstrate that our method outperforms the
state-of-theart methods in terms of BLEU and METEOR.