---
layout: publication
title: 'OBJ2TEXT: Generating Visually Descriptive Language From Object Layouts'
authors: Xuwang Yin, Vicente Ordonez
conference: Proceedings of the 2017 Conference on Empirical Methods in Natural Language
  Processing
year: 2017
bibkey: yin2017obj2text
citations: 62
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1707.07102'}]
tags: ["EMNLP"]
short_authors: Xuwang Yin, Vicente Ordonez
---
Generating captions for images is a task that has recently received
considerable attention. In this work we focus on caption generation for
abstract scenes, or object layouts where the only information provided is a set
of objects and their locations. We propose OBJ2TEXT, a sequence-to-sequence
model that encodes a set of objects and their locations as an input sequence
using an LSTM network, and decodes this representation using an LSTM language
model. We show that our model, despite encoding object layouts as a sequence,
can represent spatial relationships between objects, and generate descriptions
that are globally coherent and semantically relevant. We test our approach in a
task of object-layout captioning by using only object annotations as inputs. We
additionally show that our model, combined with a state-of-the-art object
detector, improves an image captioning model from 0.863 to 0.950 (CIDEr score)
in the test benchmark of the standard MS-COCO Captioning task.