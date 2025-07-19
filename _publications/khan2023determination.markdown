---
layout: publication
title: Determination Of Toxic Comments And Unintended Model Bias Minimization Using
  Deep Learning Approach
authors: Khan Md Azim
conference: 2018 17th IEEE International Conference on Machine Learning and Applications
  (ICMLA)
year: 2023
bibkey: khan2023determination
citations: 67
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2311.04789'}]
tags: [Training Techniques, Attention Mechanism, Ethics And Bias, BERT, Transformer,
  Model Architecture, ICML, Applications, Fine Tuning]
---
Online conversations can be toxic and subjected to threats, abuse, or
harassment. To identify toxic text comments, several deep learning and machine
learning models have been proposed throughout the years. However, recent
studies demonstrate that because of the imbalances in the training data, some
models are more likely to show unintended biases including gender bias and
identity bias. In this research, our aim is to detect toxic comment and reduce
the unintended bias concerning identity features such as race, gender, sex,
religion by fine-tuning an attention based model called BERT(Bidirectional
Encoder Representation from Transformers). We apply weighted loss to address
the issue of unbalanced data and compare the performance of a fine-tuned BERT
model with a traditional Logistic Regression model in terms of classification
and bias minimization. The Logistic Regression model with the TFIDF vectorizer
achieve 57.1% accuracy, and fine-tuned BERT model's accuracy is 89%. Code is
available at
https://github.com/zim10/Determine_Toxic_comment_and_identity_bias.git