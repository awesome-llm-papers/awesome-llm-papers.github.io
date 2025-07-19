---
layout: publication
title: Pre-trained Summarization Distillation
authors: Shleifer Sam, Rush Alexander M.
conference: Arxiv
year: 2020
bibkey: shleifer2020pre
citations: 57
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2010.13002'}]
tags: [Training Techniques, Distillation, Alt, BERT, Transformer, Model Architecture,
  Efficiency And Optimization, Fine Tuning, Datasets]
---
Recent state-of-the-art approaches to summarization utilize large pre-trained
Transformer models. Distilling these models to smaller student models has
become critically important for practical use; however there are many different
distillation methods proposed by the NLP literature. Recent work on distilling
BERT for classification and regression tasks shows strong performance using
direct knowledge distillation. Alternatively, machine translation practitioners
distill using pseudo-labeling, where a small model is trained on the
translations of a larger model. A third, simpler approach is to 'shrink and
fine-tune' (SFT), which avoids any explicit distillation by copying parameters
to a smaller student model and then fine-tuning. We compare these three
approaches for distillation of Pegasus and BART, the current and former state
of the art, pre-trained summarization models, and find that SFT outperforms
knowledge distillation and pseudo-labeling on the CNN/DailyMail dataset, but
under-performs pseudo-labeling on the more abstractive XSUM dataset. PyTorch
Code and checkpoints of different sizes are available through Hugging Face
transformers here http://tiny.cc/4iy0tz.