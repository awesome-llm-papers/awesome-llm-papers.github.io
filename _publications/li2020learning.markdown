---
layout: publication
title: Learning Compact Reward For Image Captioning
authors: Li Nannan, Chen Zhenzhong
conference: 2017 IEEE Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2020
bibkey: li2020learning
citations: 214
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2003.10925'}]
tags: [CVPR, Reinforcement Learning, Training Techniques, Security]
---
Adversarial learning has shown its advances in generating natural and diverse
descriptions in image captioning. However, the learned reward of existing
adversarial methods is vague and ill-defined due to the reward ambiguity
problem. In this paper, we propose a refined Adversarial Inverse Reinforcement
Learning (rAIRL) method to handle the reward ambiguity problem by disentangling
reward for each word in a sentence, as well as achieve stable adversarial
training by refining the loss function to shift the generator towards Nash
equilibrium. In addition, we introduce a conditional term in the loss function
to mitigate mode collapse and to increase the diversity of the generated
descriptions. Our experiments on MS COCO and Flickr30K show that our method can
learn compact reward for image captioning.