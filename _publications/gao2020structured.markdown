---
layout: publication
title: Structured Multimodal Attentions For Textvqa
authors: Gao et al.
conference: IEEE Transactions on Pattern Analysis and Machine Intelligence
year: 2020
bibkey: gao2020structured
citations: 51
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2006.00753'}]
tags: [Model Architecture, Training Techniques, Evaluation, LLM for Code, Multimodal
    Models, Datasets, Attention Mechanism]
---
In this paper, we propose an end-to-end structured multimodal attention (SMA)
neural network to mainly solve the first two issues above. SMA first uses a
structural graph representation to encode the object-object, object-text and
text-text relationships appearing in the image, and then designs a multimodal
graph attention network to reason over it. Finally, the outputs from the above
modules are processed by a global-local attentional answering module to produce
an answer splicing together tokens from both OCR and general vocabulary
iteratively by following M4C. Our proposed model outperforms the SoTA models on
TextVQA dataset and two tasks of ST-VQA dataset among all models except
pre-training based TAP. Demonstrating strong reasoning ability, it also won
first place in TextVQA Challenge 2020. We extensively test different OCR
methods on several reasoning models and investigate the impact of gradually
increased OCR performance on TextVQA benchmark. With better OCR results,
different models share dramatic improvement over the VQA accuracy, but our
model benefits most blessed by strong textual-visual reasoning ability. To
grant our method an upper bound and make a fair testing base available for
further works, we also provide human-annotated ground-truth OCR annotations for
the TextVQA dataset, which were not given in the original release. The code and
ground-truth OCR annotations for the TextVQA dataset are available at
https://github.com/ChenyuGAO-CS/SMA