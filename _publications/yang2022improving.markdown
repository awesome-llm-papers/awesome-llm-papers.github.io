---
layout: publication
title: Improving Stability Of Fine-tuning Pretrained Language Models Via Component-wise
  Gradient Norm Clipping
authors: Chenghao Yang, Xuezhe Ma
conference: 2022 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2022
bibkey: yang2022improving
citations: 89
additional_links: [{name: Code, url: 'https://github.com/yangalan123/FineTuningStability'},
  {name: Paper, url: 'https://arxiv.org/abs/2210.10325'}]
tags: ["CVPR", "Fine-Tuning", "Training Techniques"]
short_authors: Chenghao Yang, Xuezhe Ma
---
Fine-tuning over large pretrained language models (PLMs) has established many
state-of-the-art results. Despite its superior performance, such fine-tuning
can be unstable, resulting in significant variance in performance and potential
risks for practical applications. Previous works have attributed such
instability to the catastrophic forgetting problem in the top layers of PLMs,
which indicates iteratively that fine-tuning layers in a top-down manner is a
promising solution. In this paper, we first point out that this method does not
always work out due to the different convergence speeds of different
layers/modules. Inspired by this observation, we propose a simple
component-wise gradient norm clipping method to adjust the convergence speed
for different components. Experiment results demonstrate that our method
achieves consistent improvements in terms of generalization performance,
convergence speed, and training stability. The codebase can be found at
https://github.com/yangalan123/FineTuningStability.