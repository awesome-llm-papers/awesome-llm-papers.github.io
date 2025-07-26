---
layout: publication
title: Zero-shot Cross-lingual Classification Using Multilingual Neural Machine Translation
authors: Akiko Eriguchi, Melvin Johnson, Orhan Firat, Hideto Kazawa, Wolfgang Macherey
conference: Arxiv
year: 2018
bibkey: eriguchi2018zero
citations: 80
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1809.04686'}]
tags: ["Evaluation", "Training Techniques"]
short_authors: Eriguchi et al.
---
Transferring representations from large supervised tasks to downstream tasks
has shown promising results in AI fields such as Computer Vision and Natural
Language Processing (NLP). In parallel, the recent progress in Machine
Translation (MT) has enabled one to train multilingual Neural MT (NMT) systems
that can translate between multiple languages and are also capable of
performing zero-shot translation. However, little attention has been paid to
leveraging representations learned by a multilingual NMT system to enable
zero-shot multilinguality in other NLP tasks. In this paper, we demonstrate a
simple framework, a multilingual Encoder-Classifier, for cross-lingual transfer
learning by reusing the encoder from a multilingual NMT system and stitching it
with a task-specific classifier component. Our proposed model achieves
significant improvements in the English setup on three benchmark tasks - Amazon
Reviews, SST and SNLI. Further, our system can perform classification in a new
language for which no classification data was seen during training, showing
that zero-shot classification is possible and remarkably competitive. In order
to understand the underlying factors contributing to this finding, we conducted
a series of analyses on the effect of the shared vocabulary, the training data
type for NMT, classifier complexity, encoder representation power, and model
generalization on zero-shot performance. Our results provide strong evidence
that the representations learned from multilingual NMT systems are widely
applicable across languages and tasks.