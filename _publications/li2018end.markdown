---
layout: publication
title: End-to-end Video Captioning With Multitask Reinforcement Learning
authors: Lijun Li, Boqing Gong
conference: 2019 IEEE Winter Conference on Applications of Computer Vision (WACV)
year: 2019
bibkey: li2018end
citations: 74
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1803.07950'}]
tags: ["Applications", "Datasets", "Evaluation", "Reinforcement Learning", "Training Techniques"]
short_authors: Lijun Li, Boqing Gong
---
Although end-to-end (E2E) learning has led to impressive progress on a
variety of visual understanding tasks, it is often impeded by hardware
constraints (e.g., GPU memory) and is prone to overfitting. When it comes to
video captioning, one of the most challenging benchmark tasks in computer
vision, those limitations of E2E learning are especially amplified by the fact
that both the input videos and output captions are lengthy sequences. Indeed,
state-of-the-art methods for video captioning process video frames by
convolutional neural networks and generate captions by unrolling recurrent
neural networks. If we connect them in an E2E manner, the resulting model is
both memory-consuming and data-hungry, making it extremely hard to train. In
this paper, we propose a multitask reinforcement learning approach to training
an E2E video captioning model. The main idea is to mine and construct as many
effective tasks (e.g., attributes, rewards, and the captions) as possible from
the human captioned videos such that they can jointly regulate the search space
of the E2E neural network, from which an E2E video captioning model can be
found and generalized to the testing phase. To the best of our knowledge, this
is the first video captioning model that is trained end-to-end from the raw
video input to the caption output. Experimental results show that such a model
outperforms existing ones to a large margin on two benchmark video captioning
datasets.