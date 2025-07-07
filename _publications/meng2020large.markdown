---
layout: publication
title: 'Openvidial: A Large-scale, Open-domain Dialogue Dataset With Visual Contexts'
authors: Yuxian Meng et al.
conference: Arxiv
year: 2020
citations: 17
bibkey: meng2020large
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2012.15015'}]
tags: [RAG]
---
When humans converse, what a speaker will say next significantly depends on
what he sees. Unfortunately, existing dialogue models generate dialogue
utterances only based on preceding textual contexts, and visual contexts are
rarely considered. This is due to a lack of a large-scale multi-module dialogue
dataset with utterances paired with visual contexts. In this paper, we release
\{\bf OpenViDial\}, a large-scale multi-module dialogue dataset. The dialogue
turns and visual contexts are extracted from movies and TV series, where each
dialogue turn is paired with the corresponding visual context in which it takes
place. OpenViDial contains a total number of 1.1 million dialogue turns, and
thus 1.1 million visual contexts stored in images. Based on this dataset, we
propose a family of encoder-decoder models leveraging both textual and visual
contexts, from coarse-grained image features extracted from CNNs to
fine-grained object features extracted from Faster R-CNNs. We observe that
visual information significantly improves dialogue generation qualities,
verifying the necessity of integrating multi-modal features for dialogue
learning. Our work marks an important step towards large-scale multi-modal
dialogue learning.