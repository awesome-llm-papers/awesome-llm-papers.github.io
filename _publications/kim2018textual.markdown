---
layout: publication
title: Textual Explanations For Self-driving Vehicles
authors: Jinkyu Kim, Anna Rohrbach, Trevor Darrell, John Canny, Zeynep Akata
conference: Lecture Notes in Computer Science
year: 2018
bibkey: kim2018textual
citations: 246
additional_links: [{name: Code, url: 'https://github.com/JinkyuKimUCB/explainable-deep-driving'},
  {name: Paper, url: 'https://arxiv.org/abs/1807.11546'}]
tags: ["Datasets", "Has Code"]
short_authors: Kim et al.
---
Deep neural perception and control networks have become key components of
self-driving vehicles. User acceptance is likely to benefit from
easy-to-interpret textual explanations which allow end-users to understand what
triggered a particular behavior. Explanations may be triggered by the neural
controller, namely introspective explanations, or informed by the neural
controller's output, namely rationalizations. We propose a new approach to
introspective explanations which consists of two parts. First, we use a visual
(spatial) attention model to train a convolutional network end-to-end from
images to the vehicle control commands, i.e., acceleration and change of
course. The controller's attention identifies image regions that potentially
influence the network's output. Second, we use an attention-based video-to-text
model to produce textual explanations of model actions. The attention maps of
controller and explanation model are aligned so that explanations are grounded
in the parts of the scene that mattered to the controller. We explore two
approaches to attention alignment, strong- and weak-alignment. Finally, we
explore a version of our model that generates rationalizations, and compare
with introspective explanations on the same video segments. We evaluate these
models on a novel driving dataset with ground-truth human explanations, the
Berkeley DeepDrive eXplanation (BDD-X) dataset. Code is available at
https://github.com/JinkyuKimUCB/explainable-deep-driving.