---
layout: publication
title: Learning To Generalize To New Compositions In Image Understanding
authors: Yuval Atzmon, Jonathan Berant, Vahid Kezami, Amir Globerson, Gal Chechik
conference: Arxiv
year: 2016
bibkey: atzmon2016learning
citations: 61
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1608.07639'}]
tags: ["Datasets", "Training Techniques"]
short_authors: Atzmon et al.
---
Recurrent neural networks have recently been used for learning to describe
images using natural language. However, it has been observed that these models
generalize poorly to scenes that were not observed during training, possibly
depending too strongly on the statistics of the text in the training data. Here
we propose to describe images using short structured representations, aiming to
capture the crux of a description. These structured representations allow us to
tease-out and evaluate separately two types of generalization: standard
generalization to new images with similar scenes, and generalization to new
combinations of known entities. We compare two learning approaches on the
MS-COCO dataset: a state-of-the-art recurrent network based on an LSTM (Show,
Attend and Tell), and a simple structured prediction model on top of a deep
network. We find that the structured model generalizes to new compositions
substantially better than the LSTM, ~7 times the accuracy of predicting
structured representations. By providing a concrete method to quantify
generalization for unseen combinations, we argue that structured
representations and compositional splits are a useful benchmark for image
captioning, and advocate compositional models that capture linguistic and
visual structure.