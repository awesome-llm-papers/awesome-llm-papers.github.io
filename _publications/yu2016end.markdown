---
layout: publication
title: End-to-end Concept Word Detection For Video Captioning, Retrieval, And Question
  Answering
authors: Yu et al.
conference: 2017 IEEE Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2016
bibkey: yu2016end
citations: 142
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1610.02947'}]
tags: [CVPR, Model Architecture, Training Techniques, Attention Mechanism]
---
We propose a high-level concept word detector that can be integrated with any
video-to-language models. It takes a video as input and generates a list of
concept words as useful semantic priors for language generation models. The
proposed word detector has two important properties. First, it does not require
any external knowledge sources for training. Second, the proposed word detector
is trainable in an end-to-end manner jointly with any video-to-language models.
To maximize the values of detected words, we also develop a semantic attention
mechanism that selectively focuses on the detected concept words and fuse them
with the word encoding and decoding in the language model. In order to
demonstrate that the proposed approach indeed improves the performance of
multiple video-to-language tasks, we participate in four tasks of LSMDC 2016.
Our approach achieves the best accuracies in three of them, including
fill-in-the-blank, multiple-choice test, and movie retrieval. We also attain
comparable performance for the other task, movie description.