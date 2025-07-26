---
layout: publication
title: A Study Of BFLOAT16 For Deep Learning Training
authors: Dhiraj Kalamkar, Dheevatsa Mudigere, Naveen Mellempudi, Dipankar Das, Kunal
  Banerjee, Sasikanth Avancha, Dharma Teja Vooturi, Nataraj Jammalamadaka, Jianyu
  Huang, Hector Yuen, Jiyan Yang, Jongsoo Park, Alexander Heinecke, Evangelos Georganas,
  Sudarshan Srinivasan, Abhisek Kundu, Misha Smelyanskiy, Bharat Kaul, Pradeep Dubey
conference: Arxiv
year: 2019
bibkey: kalamkar2019study
citations: 125
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1905.12322'}]
tags: ["Training Techniques"]
short_authors: Kalamkar et al.
---
This paper presents the first comprehensive empirical study demonstrating the
efficacy of the Brain Floating Point (BFLOAT16) half-precision format for Deep
Learning training across image classification, speech recognition, language
modeling, generative networks and industrial recommendation systems. BFLOAT16
is attractive for Deep Learning training for two reasons: the range of values
it can represent is the same as that of IEEE 754 floating-point format (FP32)
and conversion to/from FP32 is simple. Maintaining the same range as FP32 is
important to ensure that no hyper-parameter tuning is required for convergence;
e.g., IEEE 754 compliant half-precision floating point (FP16) requires
hyper-parameter tuning. In this paper, we discuss the flow of tensors and
various key operations in mixed precision training, and delve into details of
operations, such as the rounding modes for converting FP32 tensors to BFLOAT16.
We have implemented a method to emulate BFLOAT16 operations in Tensorflow,
Caffe2, IntelCaffe, and Neon for our experiments. Our results show that deep
learning training using BFLOAT16 tensors achieves the same state-of-the-art
(SOTA) results across domains as FP32 tensors in the same number of iterations
and with no changes to hyper-parameters.