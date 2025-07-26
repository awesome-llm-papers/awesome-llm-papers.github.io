---
layout: publication
title: Training Neural Response Selection For Task-oriented Dialogue Systems
authors: "Matthew Henderson, Ivan Vuli\u0107, Daniela Gerz, I\xF1igo Casanueva, Pawe\u0142\
  \ Budzianowski, Sam Coope, Georgios Spithourakis, Tsung-hsien Wen, Nikola Mrk\u0161\
  i\u0107, Pei-hao Su"
conference: Proceedings of the 57th Annual Meeting of the Association for Computational
  Linguistics
year: 2019
bibkey: henderson2019training
citations: 86
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1906.01543'}]
tags: ["Training Techniques"]
short_authors: Henderson et al.
---
Despite their popularity in the chatbot literature, retrieval-based models
have had modest impact on task-oriented dialogue systems, with the main
obstacle to their application being the low-data regime of most task-oriented
dialogue tasks. Inspired by the recent success of pretraining in language
modelling, we propose an effective method for deploying response selection in
task-oriented dialogue. To train response selection models for task-oriented
dialogue tasks, we propose a novel method which: 1) pretrains the response
selection model on large general-domain conversational corpora; and then 2)
fine-tunes the pretrained model for the target dialogue domain, relying only on
the small in-domain dataset to capture the nuances of the given dialogue
domain. Our evaluation on six diverse application domains, ranging from
e-commerce to banking, demonstrates the effectiveness of the proposed training
method.