---
layout: publication
title: Visual Dialog
authors: "Abhishek Das, Satwik Kottur, Khushi Gupta, Avi Singh, Deshraj Yadav, Jos\xE9\
  \ M. F. Moura, Devi Parikh, Dhruv Batra"
conference: Arxiv
year: 2017
bibkey: das2016visual
citations: 552
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1611.08669'}]
tags: ["Datasets", "Evaluation"]
short_authors: Das et al.
---
We introduce the task of Visual Dialog, which requires an AI agent to hold a
meaningful dialog with humans in natural, conversational language about visual
content. Specifically, given an image, a dialog history, and a question about
the image, the agent has to ground the question in image, infer context from
history, and answer the question accurately. Visual Dialog is disentangled
enough from a specific downstream task so as to serve as a general test of
machine intelligence, while being grounded in vision enough to allow objective
evaluation of individual responses and benchmark progress. We develop a novel
two-person chat data-collection protocol to curate a large-scale Visual Dialog
dataset (VisDial). VisDial v0.9 has been released and contains 1 dialog with 10
question-answer pairs on ~120k images from COCO, with a total of ~1.2M dialog
question-answer pairs.
  We introduce a family of neural encoder-decoder models for Visual Dialog with
3 encoders -- Late Fusion, Hierarchical Recurrent Encoder and Memory Network --
and 2 decoders (generative and discriminative), which outperform a number of
sophisticated baselines. We propose a retrieval-based evaluation protocol for
Visual Dialog where the AI agent is asked to sort a set of candidate answers
and evaluated on metrics such as mean-reciprocal-rank of human response. We
quantify gap between machine and human performance on the Visual Dialog task
via human studies. Putting it all together, we demonstrate the first 'visual
chatbot'! Our dataset, code, trained models and visual chatbot are available on
https://visualdialog.org