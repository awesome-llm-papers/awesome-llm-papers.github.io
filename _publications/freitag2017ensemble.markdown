---
layout: publication
title: Ensemble Distillation For Neural Machine Translation
authors: Markus Freitag, Yaser Al-onaizan, Baskaran Sankaran
conference: Arxiv
year: 2017
bibkey: freitag2017ensemble
citations: 67
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1702.01802'}]
tags: ["Efficiency", "Model Architecture", "Training Techniques"]
short_authors: Markus Freitag, Yaser Al-onaizan, Baskaran Sankaran
---
Knowledge distillation describes a method for training a student network to
perform better by learning from a stronger teacher network. Translating a
sentence with an Neural Machine Translation (NMT) engine is time expensive and
having a smaller model speeds up this process. We demonstrate how to transfer
the translation quality of an ensemble and an oracle BLEU teacher network into
a single NMT system. Further, we present translation improvements from a
teacher network that has the same architecture and dimensions of the student
network. As the training of the student model is still expensive, we introduce
a data filtering method based on the knowledge of the teacher model that not
only speeds up the training, but also leads to better translation quality. Our
techniques need no code change and can be easily reproduced with any NMT
architecture to speed up the decoding process.