---
layout: publication
title: Fooling Neural Network Interpretations Via Adversarial Model Manipulation
authors: Juyeon Heo, Sunghwan Joo, Taesup Moon
conference: NeurIPS 2019 ICCV workshop 2019
year: 2019
bibkey: heo2019fooling
citations: 67
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1902.02041'}]
tags: ["ICCV", "NEURIPS", "Security"]
short_authors: Juyeon Heo, Sunghwan Joo, Taesup Moon
---
We ask whether the neural network interpretation methods can be fooled via
adversarial model manipulation, which is defined as a model fine-tuning step
that aims to radically alter the explanations without hurting the accuracy of
the original models, e.g., VGG19, ResNet50, and DenseNet121. By incorporating
the interpretation results directly in the penalty term of the objective
function for fine-tuning, we show that the state-of-the-art saliency map based
interpreters, e.g., LRP, Grad-CAM, and SimpleGrad, can be easily fooled with
our model manipulation. We propose two types of fooling, Passive and Active,
and demonstrate such foolings generalize well to the entire validation set as
well as transfer to other interpretation methods. Our results are validated by
both visually showing the fooled explanations and reporting quantitative
metrics that measure the deviations from the original explanations. We claim
that the stability of neural network interpretation method with respect to our
adversarial model manipulation is an important criterion to check for
developing robust and reliable neural network interpretation method.