---
layout: publication
title: 'Unified-io 2: Scaling Autoregressive Multimodal Models With Vision, Language,
  Audio, And Action'
authors: Jiasen Lu et al.
conference: 2024 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2023
citations: 15
bibkey: lu2023unified
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2312.17172'}]
tags: [Model Architecture, GPT, Transformer, Multimodal Models, Prompting, Pre-Training,
  Training Techniques, Evaluation]
---
We present Unified-IO 2, the first autoregressive multimodal model that is
capable of understanding and generating image, text, audio, and action. To
unify different modalities, we tokenize inputs and outputs -- images, text,
audio, action, bounding boxes, etc., into a shared semantic space and then
process them with a single encoder-decoder transformer model. Since training
with such diverse modalities is challenging, we propose various architectural
improvements to stabilize model training. We train our model from scratch on a
large multimodal pre-training corpus from diverse sources with a multimodal
mixture of denoisers objective. To learn an expansive set of skills, such as
following multimodal instructions, we construct and finetune on an ensemble of
120 datasets with prompts and augmentations. With a single unified model,
Unified-IO 2 achieves state-of-the-art performance on the GRIT benchmark and
strong results in more than 35 benchmarks, including image generation and
understanding, natural language understanding, video and audio understanding,
and robotic manipulation. We release all our models to the research community.