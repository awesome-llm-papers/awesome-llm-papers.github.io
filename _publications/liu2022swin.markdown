---
layout: publication
title: 'Swin Transformer V2: Scaling Up Capacity And Resolution'
authors: Ze Liu, Han Hu, Yutong Lin, Zhuliang Yao, Zhenda Xie, Yixuan Wei, Jia Ning,
  Yue Cao, Zheng Zhang, Li Dong, Furu Wei, Baining Guo
conference: 2022 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2022
bibkey: liu2022swin
citations: 1328
additional_links: [{name: Code, url: 'https://github.com/microsoft/Swin-Transformer'},
  {name: Paper, url: 'https://arxiv.org/abs/2111.09883'}]
tags: ["CVPR", "Model Architecture"]
short_authors: Liu et al.
---
Large-scale NLP models have been shown to significantly improve the
performance on language tasks with no signs of saturation. They also
demonstrate amazing few-shot capabilities like that of human beings. This paper
aims to explore large-scale models in computer vision. We tackle three major
issues in training and application of large vision models, including training
instability, resolution gaps between pre-training and fine-tuning, and hunger
on labelled data. Three main techniques are proposed: 1) a residual-post-norm
method combined with cosine attention to improve training stability; 2) A
log-spaced continuous position bias method to effectively transfer models
pre-trained using low-resolution images to downstream tasks with
high-resolution inputs; 3) A self-supervised pre-training method, SimMIM, to
reduce the needs of vast labeled images. Through these techniques, this paper
successfully trained a 3 billion-parameter Swin Transformer V2 model, which is
the largest dense vision model to date, and makes it capable of training with
images of up to 1,536\\(\times\\)1,536 resolution. It set new performance records
on 4 representative vision tasks, including ImageNet-V2 image classification,
COCO object detection, ADE20K semantic segmentation, and Kinetics-400 video
action classification. Also note our training is much more efficient than that
in Google's billion-level visual models, which consumes 40 times less labelled
data and 40 times less training time. Code is available at
https://github.com/microsoft/Swin-Transformer.