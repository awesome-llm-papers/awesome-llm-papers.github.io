---
layout: publication
title: 'Read Like Humans: Autonomous, Bidirectional And Iterative Language Modeling
  For Scene Text Recognition'
authors: Fang et al.
conference: 2021 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2021
bibkey: fang2021read
citations: 290
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2103.06495'}]
tags: [Training Techniques, Evaluation, CVPR, Language Modeling, Datasets]
---
Linguistic knowledge is of great benefit to scene text recognition. However,
how to effectively model linguistic rules in end-to-end deep networks remains a
research challenge. In this paper, we argue that the limited capacity of
language models comes from: 1) implicitly language modeling; 2) unidirectional
feature representation; and 3) language model with noise input.
Correspondingly, we propose an autonomous, bidirectional and iterative ABINet
for scene text recognition. Firstly, the autonomous suggests to block gradient
flow between vision and language models to enforce explicitly language
modeling. Secondly, a novel bidirectional cloze network (BCN) as the language
model is proposed based on bidirectional feature representation. Thirdly, we
propose an execution manner of iterative correction for language model which
can effectively alleviate the impact of noise input. Additionally, based on the
ensemble of iterative predictions, we propose a self-training method which can
learn from unlabeled images effectively. Extensive experiments indicate that
ABINet has superiority on low-quality images and achieves state-of-the-art
results on several mainstream benchmarks. Besides, the ABINet trained with
ensemble self-training shows promising improvement in realizing human-level
recognition. Code is available at https://github.com/FangShancheng/ABINet.