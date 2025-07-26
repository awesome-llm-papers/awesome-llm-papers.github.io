---
layout: publication
title: Sequence-to-sequence Data Augmentation For Dialogue Language Understanding
authors: Yutai Hou, Yijia Liu, Wanxiang Che, Ting Liu
conference: Arxiv
year: 2018
bibkey: hou2018sequence
citations: 121
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1807.01554'}]
tags: ["Datasets", "Training Techniques"]
short_authors: Hou et al.
---
In this paper, we study the problem of data augmentation for language
understanding in task-oriented dialogue system. In contrast to previous work
which augments an utterance without considering its relation with other
utterances, we propose a sequence-to-sequence generation based data
augmentation framework that leverages one utterance's same semantic
alternatives in the training data. A novel diversity rank is incorporated into
the utterance representation to make the model produce diverse utterances and
these diversely augmented utterances help to improve the language understanding
module. Experimental results on the Airline Travel Information System dataset
and a newly created semantic frame annotation on Stanford Multi-turn,
Multidomain Dialogue Dataset show that our framework achieves significant
improvements of 6.38 and 10.04 F-scores respectively when only a training set
of hundreds utterances is represented. Case studies also confirm that our
method generates diverse utterances.