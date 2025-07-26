---
layout: publication
title: Conversational Transfer Learning For Emotion Recognition
authors: Devamanyu Hazarika, Soujanya Poria, Roger Zimmermann, Rada Mihalcea
conference: Information Fusion
year: 2020
bibkey: hazarika2019conversational
citations: 87
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1910.04980'}]
tags: ["Fine-Tuning", "Training Techniques"]
short_authors: Hazarika et al.
---
Recognizing emotions in conversations is a challenging task due to the
presence of contextual dependencies governed by self- and inter-personal
influences. Recent approaches have focused on modeling these dependencies
primarily via supervised learning. However, purely supervised strategies demand
large amounts of annotated data, which is lacking in most of the available
corpora in this task. To tackle this challenge, we look at transfer learning
approaches as a viable alternative. Given the large amount of available
conversational data, we investigate whether generative conversational models
can be leveraged to transfer affective knowledge for detecting emotions in
context. We propose an approach, TL-ERC, where we pre-train a hierarchical
dialogue model on multi-turn conversations (source) and then transfer its
parameters to a conversational emotion classifier (target). In addition to the
popular practice of using pre-trained sentence encoders, our approach also
incorporates recurrent parameters that model inter-sentential context across
the whole conversation. Based on this idea, we perform several experiments
across multiple datasets and find improvement in performance and robustness
against limited training data. TL-ERC also achieves better validation
performances in significantly fewer epochs. Overall, we infer that knowledge
acquired from dialogue generators can indeed help recognize emotions in
conversations.