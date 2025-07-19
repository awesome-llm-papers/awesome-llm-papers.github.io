---
layout: publication
title: Mixup Training Leads To Reduced Overfitting And Improved Calibration For The
  Transformer Architecture
authors: Zhang Wancong, Vaidya Ieshan
conference: Arxiv
year: 2021
bibkey: zhang2021mixup
citations: 203
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2102.11402'}]
tags: [Model Architecture, Transformer, Training Techniques, BERT]
---
MixUp is a computer vision data augmentation technique that uses convex
interpolations of input data and their labels to enhance model generalization
during training. However, the application of MixUp to the natural language
understanding (NLU) domain has been limited, due to the difficulty of
interpolating text directly in the input space. In this study, we propose MixUp
methods at the Input, Manifold, and sentence embedding levels for the
transformer architecture, and apply them to finetune the BERT model for a
diverse set of NLU tasks. We find that MixUp can improve model performance, as
well as reduce test loss and model calibration error by up to 50%.