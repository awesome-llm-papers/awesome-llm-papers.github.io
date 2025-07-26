---
layout: publication
title: Revisiting Visual Question Answering Baselines
authors: Allan Jabri, Armand Joulin, Laurens van Der Maaten
conference: Lecture Notes in Computer Science
year: 2016
bibkey: jabri2016revisiting
citations: 247
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1606.08390'}]
tags: ["Datasets"]
short_authors: Allan Jabri, Armand Joulin, Laurens van Der Maaten
---
Visual question answering (VQA) is an interesting learning setting for
evaluating the abilities and shortcomings of current systems for image
understanding. Many of the recently proposed VQA systems include attention or
memory mechanisms designed to support "reasoning". For multiple-choice VQA,
nearly all of these systems train a multi-class classifier on image and
question features to predict an answer. This paper questions the value of these
common practices and develops a simple alternative model based on binary
classification. Instead of treating answers as competing choices, our model
receives the answer as input and predicts whether or not an
image-question-answer triplet is correct. We evaluate our model on the Visual7W
Telling and the VQA Real Multiple Choice tasks, and find that even simple
versions of our model perform competitively. Our best model achieves
state-of-the-art performance on the Visual7W Telling task and compares
surprisingly well with the most complex systems proposed for the VQA Real
Multiple Choice task. We explore variants of the model and study its
transferability between both datasets. We also present an error analysis of our
model that suggests a key problem of current VQA systems lies in the lack of
visual grounding of concepts that occur in the questions and answers. Overall,
our results suggest that the performance of current VQA systems is not
significantly better than that of systems designed to exploit dataset biases.