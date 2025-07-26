---
layout: publication
title: Translating Math Formula Images To Latex Sequences Using Deep Neural Networks
  With Sequence-level Training
authors: Zelun Wang, Jyh-charn Liu
conference: International Journal on Document Analysis and Recognition (IJDAR)
year: 2020
bibkey: wang2019translating
citations: 71
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1908.11415'}]
tags: ["Datasets", "Evaluation", "Model Architecture", "Training Techniques"]
short_authors: Zelun Wang, Jyh-charn Liu
---
In this paper we propose a deep neural network model with an encoder-decoder
architecture that translates images of math formulas into their LaTeX markup
sequences. The encoder is a convolutional neural network (CNN) that transforms
images into a group of feature maps. To better capture the spatial
relationships of math symbols, the feature maps are augmented with 2D
positional encoding before being unfolded into a vector. The decoder is a
stacked bidirectional long short-term memory (LSTM) model integrated with the
soft attention mechanism, which works as a language model to translate the
encoder output into a sequence of LaTeX tokens. The neural network is trained
in two steps. The first step is token-level training using the
Maximum-Likelihood Estimation (MLE) as the objective function. At completion of
the token-level training, the sequence-level training objective function is
employed to optimize the overall model based on the policy gradient algorithm
from reinforcement learning. Our design also overcomes the exposure bias
problem by closing the feedback loop in the decoder during sequence-level
training, i.e., feeding in the predicted token instead of the ground truth
token at every time step. The model is trained and evaluated on the
IM2LATEX-100K dataset and shows state-of-the-art performance on both
sequence-based and image-based evaluation metrics.